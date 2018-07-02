<template>
<nav class="navbar navbar-expand-lg navbar-light bg-white">
  
  <button class="navbar-toggler" type="button" style="border:none" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon "></span>
  </button>
    
    <h4 class="mx-auto linha mt-3 navmob" style="color: white;"><b>LOGOX</b></h4> <i class="fa fa-headset icone navmob"></i>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item ">
        <button class="btn mx-auto menus btn-block">
            <i class="fa fa-search align-middle icone mr-4"></i>Buscar</button>
      </li>
      
    </ul>
    <form class="form-inline my-2 my-lg-0 pr-2">
        <div class="row">
        <button class="btn mx-auto menus ">
            Meu perfil<i class="fa fa-angle-down align-middle icone ml-4"></i></button>
        <i class="fa fa-user-circle icone mx-auto my-2 ml-5 mr-3"></i>
        <button style="border:none; background-color: transparent">
        <i class="fa fa-bell icone my-2 ml-3"></i><span class="badge badge-primary">4</span>
        </button>
        </div>
    </form>
  </div>
</nav>
</template>

<script>
export default {
    name: 'MenuTop'
    
}
</script>

<style src="./style.css" scoped>

</style>

