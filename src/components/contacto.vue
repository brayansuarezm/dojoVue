<template>
  <div>
    <h2>Cursos</h2>
    <ul>
        <li v-for="materia in materias">
          {{ materia }}
        </li>
    </ul>
  </div>
</template>

<script>
export default{
  data(){
    return {materias:[
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
