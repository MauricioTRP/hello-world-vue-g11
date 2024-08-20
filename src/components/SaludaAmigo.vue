<script>
export default {
  // Nombre con el cua
  name: 'SaludaAmigo',
  data() {
    return {
      nombre: 'Antonio Acevedo',
      mensaje: 'Y acevedo, acevedo y antonio'
    }
  }
}
</script>
<template>
  <p>Hola soy {{ nombre }}, {{ mensaje }}</p>
</template>
<style scoped></style>
