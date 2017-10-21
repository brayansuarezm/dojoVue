<template>
  <div>
    <h2>home</h2>
    <h1>{{tareas}}</h1>
    <input type="text" placeholder="Introducir texto" v-model="nuevaTexto">
    <input type="button" value="Enviar tarea" v-on:click="agregarTarea">

  </div>
</template>

<script>
export default{
data(){
  return {
    nuevaTexto:null,
    tareas:null
  }
},
methods:{
    agregarTarea(){
      this.tareas=this.nuevaTexto;
    },
},
}
</script>

<style>
</style>
