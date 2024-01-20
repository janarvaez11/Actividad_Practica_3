<template>
  <div class="app-container">
    <h1>Eventos en Vue con Vite</h1>
    <h2>Grupo N° 4</h2>
    <h3>Ariel Narváez - Angelo Olmedo</h3>
    <ClickHandler />
    <InputHandler />
  </div>
</template>

<script>
import ClickHandler from './components/ClickHandler.vue';
import InputHandler from './components/InputHandler.vue';

export default {
  components: {
    ClickHandler,
    InputHandler,
  },
};
</script>

<style>
/* Estilos globales si es necesario */
body {
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background: linear-gradient(to right, #36D1DC, #5B86E5); /* Cambia los colores del degradado según tus preferencias */
}

.app-container {
  text-align: center;
  padding: 20px;
  border-radius: 10px;
  background-color: rgba(255, 255, 255, 0.8); /* Fondo semi-transparente para mejorar la legibilidad */
}

button {
  padding: 10px 20px;
  border: none;
  border-radius: 20px;
  background-color: #3498db; /* Color de fondo del botón */
  color: #fff; /* Color del texto del botón */
  cursor: pointer;
  font-size: 16px;
  transition: background-color 0.3s ease; /* Agregar transición al color de fondo para un efecto suave */

  &:hover {
    background-color: #2980b9; /* Cambiar el color de fondo al pasar el ratón */
  }
}
</style>
