<!-- estudiante.vue -->
<template>
    <div>
      <h2>Estudiante</h2>
      <DatosBasicos :datos="datosBasicos" />
      <!-- Otros campos específicos del estudiante -->
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
          primerNombre: 'Pedro',
          segundoNombre: 'Pablo',
          primerApellido: 'García',
          segundoApellido: 'Fernández',
          documento: 'DNI',
          numeroDocumento: '98765432'
        }
      }
    }
  }
  </script>
  