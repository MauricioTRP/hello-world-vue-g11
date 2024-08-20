<script setup>
import NavBar from './components/NavBar.vue'
import FooterComponent from './components/FooterComponent.vue'
import CardComponent from './components/CardComponent.vue'
import SaludaAmigo from './components/SaludaAmigo.vue'

const msg = 'Vue es más wena onda aún 🍺🍺🍺🍺'
</script>

<template>
  <NavBar />
  <div class="nuestra-app">
    <h1>Vue es wena onda 🍺</h1>

    <p>{{ msg }}</p>

    <CardComponent />
    <SaludaAmigo />
  </div>
  <FooterComponent />
</template>

<style scoped>
h1 {
  color: pink;
}
</style>
