<template>
  <div id="app">
    
    <Layout/>
  </div>
</template>

<script>
import Layout from './components/Layout.vue'
import Formulario from './components/Formulario.vue'
import MenuBase from './components/MenuBase.vue'
import MenuTop from './components/MenuTop.vue'
import Perfil from './components/Perfil.vue'
import Sidenav from './components/Sidenav.vue'

export default {
  name: 'app',
  components: {
    Layout,
    Formulario,
    MenuBase,
    MenuTop,
    Perfil,
    Sidenav
  },
  data() {

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
