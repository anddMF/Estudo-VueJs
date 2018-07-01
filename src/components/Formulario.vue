<template>
<div>
<form @submit.prevent="novoUsuario">
    <div class="form-row">
        <div class="form-group col-md-5">
            <label for="nomeI"><b>Nome</b></label>
            <input type="text" v-model="nome" v-validate="'required'" name="nome" class="form-control" id="nomeI" placeholder="Digite seu nome">
            <div v-if="errors.has('nome')" class="alert linha" role="alert">
                <b>Campo requerido</b>
            </div>
        </div>
        <div class="col-md-1 "></div>
        <div class="form-group col-md-6">
            <label for="fantasiaI"><b>Nome fantasia</b></label>
            <input type="text" v-model="nomeFan" v-validate="'required'" name="nomeFan" class="form-control" id="fantasiaI" placeholder="Digite o nome fantasia">
            <div v-if="errors.has('nomeFan')" class="alert linha" role="alert">
                <b>Campo requerido</b>
            </div>
        </div>
    </div>
    <div class="form-row">
        <div class="form-group col-md-5">
            <label for="segmentoI"><b>Segmento</b></label>
            <select id="segmentoI" class="form-control ">
                <option selected>Escolha o segmento</option>
                <option v-for="(data, index) in select" :key='index'>{{ data.segmento }}</option>
            </select>
        </div>
        <div class="col-md-1 "></div>
        <div class="form-group col-md-6">
            <b>Gênero</b>
            <br>
            <div class="custom-control custom-radio custom-control-inline genero">
                <input type="radio" id="mascR" name="radioInline1" class="custom-control-input">
                <label class="custom-control-label" for="mascR">Masculino</label>
            </div>
            <div class="custom-control custom-radio custom-control-inline genero">
                <input type="radio" id="femR" name="radioInline1" class="custom-control-input">
                <label class="custom-control-label" for="femR">Feminino</label>
            </div>
        </div>
    </div>
    <hr class="mb-5 mt-5">

    <div class="form-row">
        <div class="form-group col-md-5">
            <label for="cepI"><b>Cep</b></label>
            <input type="text" class="form-control" placeholder="Digite seu cep" id="cepI">
        </div>
        <div class="col-md-1 "></div>
        <div class="form-group col-md-4">
            <label for="endI"><b>Endereço</b></label>
            <input type="text" placeholder="Digite seu endereço" class="form-control" id="endI">
        </div>
        <div class="form-group col-md-2">
            <label for="numI"><b>Numero</b></label>
            <input type="text" placeholder="Número" class="form-control" id="numI">
        </div>
    </div>
    <div class="form-row">
        <div class="form-group col-md-5">
            <label for="compI"><b>Complemento</b></label>
            <input type="text" placeholder="Digite o complemento" class="form-control" id="compI">
        </div>
        <div class="col-md-1 "></div>
        <div class="form-group col-md-4">
            <label for="cidI"><b>Cidade</b></label>
            <input type="text" placeholder="Digite sua cidade" class="form-control" id="cidI">
        </div>
        <div class="form-group col-md-2">
            <label for="ufI"><b>UF</b></label>
            <input type="text" placeholder="UF" class="form-control" id="ufI">
        </div>
    </div>
    <hr class="mb-5 mt-5">
    <div class="form-row">
        <div class="form-group col-md-4">
            <label for="compI"><b>Telefone</b></label>
            <input type="text" placeholder="(11) 99999-9999" class="form-control" id="compI">
        </div>
        <div class="form-group col-md-4">
            <label for="cidI"><b>Telefone</b></label>
            <input type="text" placeholder="(11) 99999-9999" class="form-control" id="cidI">
        </div>
        <div class="form-group col-md-4">
            <label for="ufI"><b>Telefone</b></label>
            <input type="text" placeholder="(11) 99999-9999" class="form-control" id="ufI">
        </div>
    </div>
    <br><br>
    <div class="form-row ">
        <div class="form-group ml-3 col-md-4 form-check">
            <input class="form-check-input" type="checkbox" id="inlineCheckbox2" value="option2">
            <label class="form-check-label ml-2 termos" for="inlineCheckbox2">Li e aceito os termos de condições do contrato</label>
       </div>
        <div class="form-group col-md-3">
            <p style="font-size: 20px;"><i class="fa fa-print icone"></i> Imprimir</p>
        </div>
        <div class="form-group col-md-4">
            <button type="submit" class="btn btn-block btn-primary btn-salvar">SALVAR</button>
        </div>
    </div>
</form>

</div>
</template>

<script>
export default {
  name: "Formulario",
  props: {},
  mounted() {},
  data() {
    return {
      nome: "",
      nomeFan: "",
      select: [
        { segmento: "Beleza" },
        { segmento: "Alimentação" },
        { segmento: "Comércio" }
      ]
    };
  },
  methods: {
    novoUsuario() {
      this.select.push({ segmento: this.nome });
      this.nome = "";
    }
  },
  computed: {}
};
</script>

<style src="./style.css" scoped>
</style>