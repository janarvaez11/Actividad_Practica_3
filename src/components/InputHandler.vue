<template>
  <div>
    <input type="text" :value="inputValue" @input="handleInputChange" />
    <p>Valor actual del campo de entrada: {{ inputValue }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      inputValue: '',
    };
  },
  methods: {
    handleInputChange(event) {
      this.inputValue = event.target.value;
    },
  },
};
</script>

<style scoped>
/* Estilos específicos del componente si es necesario */
</style>
