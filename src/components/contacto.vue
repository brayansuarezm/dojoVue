<template>
  <div>
    <h2>Contacto</h2>
    <ul>
        <li v-for="tarea in tareas">
          {{ tarea }}
        </li>
    </ul>
  </div>
</template>

<script>
export default{
  data(){
    return {tareas:[
      'Calculo',
      'Fisica',
      'Algebra',
      'Calidad'
    ]}
  }
}
</script>

<style>
</style>
