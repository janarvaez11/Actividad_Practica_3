<template>
  <div>
    <button @click="handleClick">Haz clic aquí</button>
  </div>
  <br>
</template>

<script>
export default {
  methods: {
    handleClick() {
      alert('¡Grupo 4 informa que hiciste clic en el botón!');
    },
  },
};
</script>

<style scoped>
/* Estilos específicos del componente si es necesario */
</style>
