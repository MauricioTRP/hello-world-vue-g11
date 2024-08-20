<script>
export default {
  // Nombre componente
  name: 'CardComponent',
  // Data, estado inicial
  data() {
    return {
      userName: 'Carlita',
      userLastName: 'Pérez'
    }
  }
}
</script>
<template>
  <div class="card">
    <h3>Nombre usuario: {{ userName }} {{ userLastName }}</h3>
  </div>
</template>
<style scoped></style>
