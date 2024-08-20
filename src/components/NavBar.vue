<script>
export default {
  name: 'NavBar',
  data() {
    return {
      nombreNegocio: 'Desafío Latam',
      opciones: ['Carreras', 'Cursos', 'Empresas'],
      sesion: 'Iniciar Sesión'
    }
  }
}
</script>
<template>
  <div>
    <nav>
      <span>{{ nombreNegocio }}</span>
      <div class="opciones">
        <span>{{ opciones[0] }}</span>
        <span>{{ opciones[1] }}</span>
        <span>{{ opciones[2] }}</span>
      </div>

      <div>
        <span>{{ sesion }}</span>
      </div>
    </nav>
  </div>
</template>

<style scoped>
nav {
  background-color: #900c3e;
  color: white;
  display: flex;
  padding: 1rem 2rem;
  justify-content: space-around;
}

.opciones {
  display: flex;
  gap: 1rem;
}
</style>
