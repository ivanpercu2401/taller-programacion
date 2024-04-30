<!-- cliente.vue -->
<template>
    <div>
      <h2>Cliente</h2>
      <DatosBasicos :datos="datosBasicos" />
      <!-- Otros campos específicos del cliente -->
    </div>
  </template>
  
  <script>
  import DatosBasicos from './datosBasicos.vue'
  
  export default {
    components: {
      DatosBasicos
    },
    data() {
      return {
        datosBasicos: {
          primerNombre: 'Juan',
          segundoNombre: 'Carlos',
          primerApellido: 'Pérez',
          segundoApellido: 'Gómez',
          documento: 'DNI',
          numeroDocumento: '12345678'
        }
      }
    }
  }
  </script>
  