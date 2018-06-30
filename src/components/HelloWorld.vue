<template>
  <div class="hello">
    <h4 class="mt-2 ml-5 mb-2">Meus dados cadastrais</h4>

    <div class="row">
        <!-- PRIMEIRO CARD -->
        <div class="ml-md-5 mb-3 pl-3 col-md-3 bg-white">
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
                <div class="col-md-5 col-sm-5 col-xs-5 mt-2 text-center mx-auto">
                    <div class="progress w-100 progresso-fundo" style="height: 10px;">
                        <div class="progress-bar progress-bar progresso" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                </div>
                <div class="col-sm-6">
                <p class="bg-primary" style="font-size:12px;">70% completo</p>
                </div>
            </div>
            <!-- /DADOS -->
            <hr>
            <!-- MENU -->
            <div class="col-md-12 col-xs-12 pt-3 pb-3 pl-1">
                <div class="row mb-2 ">
                    <div class="col-md-10 col-sm-12 col-xs-12 mx-auto">
                        <div class="row pl-3 text-center">
                            <div class="col-md-2 col-sm-2">
                                <i class="fa fa-users-cog fa-2x icone justify-content-end"></i>
                            </div>
                            <div class="col-md-9 col-sm-4 ml-md-2 col-xs-8">
                                <p class="align-middle" style="line-height: 30px;">
                                    <b>Minha conta</b>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="row  mb-2 ">
                    <div class="col-md-10 col-sm-12 col-xs-12 mx-auto">
                        <div class="row pl-3 text-center">
                            <div class="col-md-2 col-xs-2">
                                <i class="fa fa-university icone justify-content-end" style=""></i>
                            </div>
                            <div class="col-md-9 ml-md-2 col-xs-8">
                                <p class="" style="line-height: 30px;">
                                    <b>Domicílio bancário</b>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="row  mb-2 ">
                    <div class="col-md-10 col-s-12 col-xs-12 mx-auto">
                        <div class="row pl-3 text-center">
                            <div class="col-md-2 bg-white col-xs-2">
                                <i class="fa fa-edit icone justify-content-end"></i>
                            </div>
                            <div class="col-md-9 ml-md-2 col-xs-8">
                                <p class="" style="line-height: 30px;">
                                    <b>Editar cadastro</b>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="row  mb-2 ">
                    <div class="col-md-10 col-s-12 col-xs-12 mx-auto">
                        <div class="row pl-3 text-center">
                            <div class="col-md-2 bg-white col-xs-2">
                                <i class="fa fa-key fa-2x icone justify-content-end"></i>
                            </div>
                            <div class="col-md-9 ml-md-2 col-xs-8">
                                <p class="" style="line-height: 30px;">
                                    <b>Alterar senha</b>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="row">
                    <div class="col-md-10 col-s-12 col-xs-12 mx-auto">
                        <div class="row pl-3 text-center">
                            <div class="col-md-2 bg-white col-xs-2">
                                <i class="fa fa-camera fa-2x icone justify-content-end"></i>
                            </div>
                            <div class="col-md-9 ml-md-2 col-xs-8">
                                <p class="" style="line-height: 30px;">
                                    <b>Editar foto</b>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- /MENU -->
            <hr>
            <div class="col-md-12 ">
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
        <!-- /PRIMEIRO CARD -->
        <!-- <div class="col-md-1"></div> -->
        <!-- SEGUNDO CARD -->
        <div class="col-md-8 pt-2 pl-3 ml-md-4 ml-sm-2s ml-xs-1 bg-white">

            <input class="tinput" id="tab1" type="radio" name="tabs" checked>
            <label class="tlabel" for="tab1">Minha conta</label>

            <input class="tinput" id="tab2" type="radio" name="tabs">
            <label class="tlabel" for="tab2">Domicílio Bancário</label>

            <input class="tinput" id="tab3" type="radio" name="tabs">
            <label class="tlabel" for="tab3">Editar cadastro</label>

            <input class="tinput" id="tab4" type="radio" name="tabs">
            <label class="tlabel" for="tab4">Alterar senha</label>

            <input class="tinput" id="tab5" type="radio" name="tabs">
            <label class="tlabel" for="tab4">Editar foto</label>

            <section class="tsection pl-3 pr-2" id="content1">

                <h3><b>Minha conta</b></h3>
                <Formulario/>
                
            </section>

            <section class="tsection pl-3 pr-2" id="content2">
                <p>
                    Bacon ipsum dolor sit amet landjaeger sausage brisket, jerky drumstick fatback boudin ball tip turducken. Pork belly meatball
                    t-bone bresaola tail filet mignon kevin turkey ribeye shank flank doner cow kielbasa shankle. Pig swine
                    chicken hamburger, tenderloin turkey rump ball tip sirloin frankfurter meatloaf boudin brisket ham hock.
                    Hamburger venison brisket tri-tip andouille pork belly ball tip short ribs biltong meatball chuck. Pork
                    chop ribeye tail short ribs, beef hamburger meatball kielbasa rump corned beef porchetta landjaeger flank.
                    Doner rump frankfurter meatball meatloaf, cow kevin pork pork loin venison fatback spare ribs salami
                    beef ribs.
                </p>
                <p>
                    Jerky jowl pork chop tongue, kielbasa shank venison. Capicola shank pig ribeye leberkas filet mignon brisket beef kevin tenderloin
                    porchetta. Capicola fatback venison shank kielbasa, drumstick ribeye landjaeger beef kevin tail meatball
                    pastrami prosciutto pancetta. Tail kevin spare ribs ground round ham ham hock brisket shoulder. Corned
                    beef tri-tip leberkas flank sausage ham hock filet mignon beef ribs pancetta turkey.
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
                    t-bone bresaola tail filet mignon kevin turkey ribeye shank flank doner cow kielbasa shankle. Pig swine
                    chicken hamburger, tenderloin turkey rump ball tip sirloin frankfurter meatloaf boudin brisket ham hock.
                    Hamburger venison brisket tri-tip andouille pork belly ball tip short ribs biltong meatball chuck. Pork
                    chop ribeye tail short ribs, beef hamburger meatball kielbasa rump corned beef porchetta landjaeger flank.
                    Doner rump frankfurter meatball meatloaf, cow kevin pork pork loin venison fatback spare ribs salami
                    beef ribs.
                </p>
                <p>
                    Jerky jowl pork chop tongue, kielbasa shank venison. Capicola shank pig ribeye leberkas filet mignon brisket beef kevin tenderloin
                    porchetta. Capicola fatback venison shank kielbasa, drumstick ribeye landjaeger beef kevin tail meatball
                    pastrami prosciutto pancetta. Tail kevin spare ribs ground round ham ham hock brisket shoulder. Corned
                    beef tri-tip leberkas flank sausage ham hock filet mignon beef ribs pancetta turkey.
                </p>
            </section>
        </div>
        <br>
        <br>
        <!-- /SEGUNDO CARD -->
    </div>
  </div>
</template>

<script>
import Formulario from './Formulario.vue'

export default {
  name: "HelloWorld",
    components: {
    Formulario
  },
  props: {},
  data() {
    return {
      select: [
        { segmento: "Beleza" },
        { segmento: "Alimentação" },
        { segmento: "Comércio" }
      ]
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="./style.css" scoped>
</style>
