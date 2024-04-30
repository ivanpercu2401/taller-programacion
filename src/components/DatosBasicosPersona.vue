<template>
    <div>
      <label>Primer Nombre:</label>
      <input v-model="datosBasicos.primerNombre" type="text">
      <br>
      <label>Segundo Nombre:</label>
      <input v-model="datosBasicos.segundoNombre" type="text">
      <br>
      <label>Primer Apellido:</label>
      <input v-model="datosBasicos.primerApellido" type="text">
      <br>
      <label>Segundo Apellido:</label>
      <input v-model="datosBasicos.segundoApellido" type="text">
      <br>
      <label>Documento:</label>
      <input v-model="datosBasicos.documento" type="text">
      <br>
      <label>Número de Documento:</label>
      <input v-model="datosBasicos.numeroDocumento" type="text">
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        datosBasicos: {
          primerNombre: '',
          segundoNombre: '',
          primerApellido: '',
          segundoApellido: '',
          documento: '',
          numeroDocumento: ''
        }
      };
    }
  }
  </script>
  
  <style scoped>
  /* Estilos opcionales */
  </style>
  