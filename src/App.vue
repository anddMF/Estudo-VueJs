<template>
  <div id="app">

    <HelloWorld/>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Formulario from './components/Formulario.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Formulario
  }
}
</script>

<style>
@import 'https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css';
@import 'https://use.fontawesome.com/releases/v5.1.0/css/all.css';
@import 'https://fonts.googleapis.com/css?family=Montserrat';
#app {
  font-family: 'Montserrat';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body{
  background-color:#f5f5f5;
}
</style>
