<template>
  <div>
    <input type="text" v-model="message">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello'
    };
  }
};
</script>
<style scoped>
/* Estilos específicos del componente */
</style>