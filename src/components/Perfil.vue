<template>
    <div>
        <div class="row">
          <div class="col-md-12">
            <div class="mt-5 mb-3 elipse mx-auto"></div>
          </div>
        </div>

        <!-- DADOS -->
        <div class="text-center linha col-md-12">
          <h3 class="" style="color:#0385db;">Pedro Costa</h3>
          <div class="row">
            <p class="text-muted mx-auto">pedro.costa@tesla.com.br</p>
          </div>
          <div class="row">
            <p class="mx-auto">Tesla Mecânica</p>
          </div>
        </div>

        <div class="form-row">
          <div class="col-1"></div>
          <div class="col-6 mt-2 text-center mx-auto">
            <div class="progress w-100 progresso-fundo" style="height: 10px;">
              <div class="progress-bar progress-bar progresso" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>
          <div class="col-5">
            <p style="font-size:12px;">70% completo</p>
          </div>
        </div>
        <!-- /DADOS -->
        <hr>
        <!-- MENU -->
        <div class="col-md-12 col-xs-12 pt-3 pb-3 pl-1 botoes mb-4">
          <div class="row mb-2 ">
            <div class="col-md-10 col-sm-12 col-xs-12 mx-auto">
              <div class="form-row">
                <button class="btn btnm mx-auto menus abrir2 btn-block">
                  <i class="fa fa-users-cog align-middle icone mr-4"></i>Minha conta</button>
                <!-- ATIVAR FORM CELULAR -->
                <button class="btn btnm mx-auto menus btn-block abrir d-none" v-on:click="mostrarform = true">
                  <i class="fa fa-users-cog align-middle icone mr-4"></i><a href="#content1"> Minha conta</a></button>
              </div>
            </div>
          </div>
          <div class="row  mb-2 ">
            <div class="col-md-10 col-sm-12 col-xs-12 mx-auto">
              <div class="row">
                <button class="btn btnm mx-auto menus btn-block">
                  <i class="fa fa-university icone align-middle mr-4"></i>Domicílio bancário</button>
              </div>
            </div>
          </div>

          <div class="row  mb-2 ">
            <div class="col-md-10 col-s-12 col-xs-12 mx-auto">
              <div class="row">
                <button class="btn btnm mx-auto menus btn-block">
                  <i class="fa fa-edit align-middle icone mr-4"></i>Editar cadastro</button>
              </div>
            </div>
          </div>

          <div class="row  mb-2 ">
            <div class="col-md-10 col-s-12 col-xs-12 mx-auto">
              <div class="row">
                <button class="btn btnm mx-auto menus btn-block">
                  <i class="fa fa-key align-middle icone mr-4"></i>Alterar senha</button>
              </div>
            </div>
          </div>

          <div class="row">
            <div class="col-md-10 col-s-12 col-xs-12 mx-auto">
              <div class="row">
                <button class="btn btnm mx-auto menus btn-block">
                  <i class="fa fa-camera icone mr-4"></i>Editar foto</button>
              </div>
            </div>
          </div>
        </div>
        <!-- /MENU -->
        <hr>
        <div class="col-md-12 mt-4">
          <div class="row ">
            <h6 class="mx-auto">
              <i class="fa fa-headset icone "></i>
              <b class="ml-1" style="color:#0385db">Dúvidas? Fale conosco</b>
            </h6>
          </div>
        </div>
        <div class="text-center linha col-md-12">
          <h5>
            <b>0800.942.1835</b>
          </h5>
          <div class="row">
            <h5 class="mx-auto">11 3078.0876</h5>
          </div>
          <div class="row">
            <h5 class="mx-auto">11 3078.0914</h5>
          </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Perfil'
    
}
</script>
<style src="./style.css" scoped>

</style>


