<!-- empleado.vue -->
<template>
    <div>
      <h2>Empleado</h2>
      <DatosBasicos :datos="datosBasicos" />
      <!-- Otros campos específicos del empleado -->
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
          primerNombre: 'María',
          segundoNombre: '',
          primerApellido: 'López',
          segundoApellido: 'Martínez',
          documento: 'CUIL',
          numeroDocumento: '87654321'
        }
      }
    }
  }
  </script>
  