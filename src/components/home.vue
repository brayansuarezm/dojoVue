<template>
  <div>
    <h2>home</h2>
    <h1>{{texto}}</h1>
    <input type="text" placeholder="Introducir texto" v-model="nuevaTexto">
    <input type="button" value="Tomar texto" v-on:click="agregarTexto">

  </div>
</template>

<script>
export default{
data(){
  return {
    nuevaTexto:null,
    texto:null
  }
},
methods:{
    agregarTexto(){
      this.texto=this.nuevaTexto;
    },
},
}
</script>

<style>
</style>
