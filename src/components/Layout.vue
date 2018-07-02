<template>
<div class="hello">

    <MenuTop/>
    <h4 class="mt-4 ml-5 mb-2">Meus dados cadastrais</h4>
    
    <div class="row">
      <!-- PRIMEIRO CARD -->
      <div class="border ml-md-5 ml-sm-1 col-12 mb-3 pl-3 col-md-3 bg-white primeiro">
        <Perfil/>
        <br>
        <br>
        <br>
      </div>
      <!-- /PRIMEIRO CARD -->
    
      <!-- SEGUNDO CARD -->

      <div class="segundo border col-md-8 pt-2 pl-3 d-bock ml-md-4 ml-sm-2s ml-xs-1 frm bg-white">
         <!-- MENU EM TABS //funcionará fora da div  -->
        <div class="scrolling-wrapper">
          <input class="tinput" id="tab1" type="radio" name="tabs" checked>
          <label class="tlabel" for="tab1">Minha conta</label>

          <input class="tinput" id="tab2" type="radio" name="tabs">
          <label class="tlabel" for="tab2">Domicílio Bancário</label>

          <input class="tinput" id="tab3" type="radio" name="tabs">
          <label class="tlabel" for="tab3">Editar cadastro</label>

          <input class="tinput" id="tab4" type="radio" name="tabs">
          <label class="tlabel" for="tab4">Alterar senha</label>

          <input class="tinput" id="tab5" type="radio" name="tabs">
          <label class="tlabel" for="tab5">Editar foto</label>
        </div>
        <!-- FORMULÁRIO -->
        <section class="pl-3 pr-2" id="content1">
          <h3 class="mt-3">
            <b>Minha conta</b>
          </h3>
          <Formulario/>
        </section>
        <!-- /FORMULÁRIO -->

        <!-- CONTEÚDO DAS TABS -->
        <section class="tsection pl-3 pr-2" id="content2">

        </section>

        <section class="tsection pl-3 pr-2" id="content3">

        </section>

        <section class="tsection pl-3 pr-2" id="content4">

        </section>

        <br>
        <br>
        <br>
        <br>
      </div>
    </div>
    <!-- NAV TABS -->
    <MenuBase/>
    <!-- /NAV TABS -->
    <!-- /SEGUNDO CARD -->
  </div>

</template>

<script>
import Formulario from "./Formulario.vue";
import MenuBase from "./MenuBase.vue";
import MenuTop from "./MenuTop.vue";
import Perfil from "./Perfil.vue";
import Sidenav from "./Sidenav.vue"
export default {
  name: "Layout",
  components: {
    Formulario,
    MenuBase,
    MenuTop,
    Perfil,
    Sidenav
  },
  props: {},
  data() {
    return {
        mostrarform: true,
        teste: false
    };
  },
  methods: {
      
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="./style.css" scoped>
</style>
