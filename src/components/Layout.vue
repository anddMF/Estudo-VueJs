<template>
<div class="hello">
    <MenuTop/>
    <h4 class="mt-4 ml-5 mb-2">Meus dados cadastrais</h4>

    <div class="row">
      <!-- PRIMEIRO CARD -->
      <div class="ml-md-5 ml-sm-1 col-12 mb-3 pl-3 col-md-3 bg-white primeiro">
        <Perfil/>
        <br>
        <br>
        <br>
      </div>
      <!-- /PRIMEIRO CARD -->

      <!-- SEGUNDO CARD -->

      <div class="segundo col-md-8 pt-2 pl-3 d-bock ml-md-4 ml-sm-2s ml-xs-1 frm bg-white">

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
          <h3>
            <b>Minha conta</b>
          </h3>
          <Formulario/>
        </section>
        <!-- /FORMULÁRIO -->

        <section class="tsection pl-3 pr-2" id="content2">
          <p>
            Bacon ipsum dolor sit amet landjaeger sausage brisket, jerky drumstick fatback boudin ball tip turducken. Pork belly meatball
            t-bone bresaola tail filet mignon kevin turkey ribeye shank flank doner cow kielbasa shankle. Pig swine chicken
            hamburger, tenderloin turkey rump ball tip sirloin frankfurter meatloaf boudin brisket ham hock. Hamburger venison
            brisket tri-tip andouille pork belly ball tip short ribs biltong meatball chuck. Pork chop ribeye tail short
            ribs, beef hamburger meatball kielbasa rump corned beef porchetta landjaeger flank. Doner rump frankfurter meatball
            meatloaf, cow kevin pork pork loin venison fatback spare ribs salami beef ribs.
          </p>
          <p>
            Jerky jowl pork chop tongue, kielbasa shank venison. Capicola shank pig ribeye leberkas filet mignon brisket beef kevin tenderloin
            porchetta. Capicola fatback venison shank kielbasa, drumstick ribeye landjaeger beef kevin tail meatball pastrami
            prosciutto pancetta. Tail kevin spare ribs ground round ham ham hock brisket shoulder. Corned beef tri-tip leberkas
            flank sausage ham hock filet mignon beef ribs pancetta turkey.
          </p>
        </section>

        <section class="tsection pl-3 pr-2" id="content3">
          <p>
            Bacon ipsum dolor sit amet beef venison beef ribs kielbasa. Sausage pig leberkas, t-bone sirloin shoulder bresaola. Frankfurter
            rump porchetta ham. Pork belly prosciutto brisket meatloaf short ribs.
          </p>
          <p>
            Brisket meatball turkey short loin boudin leberkas meatloaf chuck andouille pork loin pastrami spare ribs pancetta rump.
            Frankfurter corned beef beef tenderloin short loin meatloaf swine ground round venison.
          </p>
        </section>

        <section class="tsection pl-3 pr-2" id="content4">
          <p>
            Bacon ipsum dolor sit amet landjaeger sausage brisket, jerky drumstick fatback boudin ball tip turducken. Pork belly meatball
            t-bone bresaola tail filet mignon kevin turkey ribeye shank flank doner cow kielbasa shankle. Pig swine chicken
            hamburger, tenderloin turkey rump ball tip sirloin frankfurter meatloaf boudin brisket ham hock. Hamburger venison
            brisket tri-tip andouille pork belly ball tip short ribs biltong.
          </p>
          <p>
            Jerky jowl pork chop tongue, kielbasa shank venison. Capicola shank pig ribeye leberkas filet mignon brisket beef kevin tenderloin
            porchetta. Capicola fatback venison shank kielbasa, drumstick ribeye landjaeger beef kevin tail meatball pastrami
            prosciutto pancetta. Tail kevin spare ribs ground round ham ham hock brisket shoulder. Corned beef tri-tip leberkas
            flank sausage ham hock filet mignon beef ribs pancetta turkey.
          </p>
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
import Perfil from "./Perfil.vue"
export default {
  name: "Layout",
  components: {
    Formulario,
    MenuBase,
    MenuTop,
    Perfil
  },
  props: {},
  data() {
    return {
        mostrarform: true,
        teste: false,
      select: [
        { segmento: "Beleza" },
        { segmento: "Alimentação" },
        { segmento: "Comércio" }
      ]
    };
  },
  methods: {
      
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="./style.css" scoped>
</style>
