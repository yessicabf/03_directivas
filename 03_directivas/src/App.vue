<template>
  <div>
    <h1>Universidad Tecnologica de Tehuacán</h1>
    
    <h3>Aplicaciones Web </h3>
    <h4>Grupo 4A</h4>
  <h1> Directivas en VUE</h1>
  
  <hr /> <!--Fragmentacion de texto    v-bind:src="texto" modificador o texto de la etiqueta*/-->
  
  <h2>v.text</h2>
  <span v-text="'Hola desde la directiva de v-text'"></span>
  <br>
  <span v-text="'Hola desde la directiva de v-text'"></span>
  <br>
  <span v-text="titulo"></span> <!--Creacion de una clase-->
  <br>
  Esta es una trasmutacion de texto con una variable prop <br>
  {{titulo}}
  
  
  </div>
  </template>
  
  
  <script>
  
  export default{
    data: () => ({   
      titulo:"Hola desde Vue.js",
    }),
  }
  
  </script>
  
  <style scoped>
  
  div{
    text-align: center;
    margin: 0px 2rem;
  
  
  }
  </style>