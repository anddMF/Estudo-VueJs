<template>
    
          <div class="sidebar-sticky col-md-3 sidebar sidebar2" >

            <ul class="nav flex-column bg-dark">
                <li class="nav-item bg-head border-bottom">
                    <h3 class=" ml-3 mt-4 mb-4" style="color: white;"><b>LOGOX</b></h3>
                </li>
              <li class="nav-item bg-dark border-bottom">
                <a class="nav-link active" style="color:white;border-color: grey !important" href="#">
                  <i class="fa fa-credit-card icone align-middle mr-2"></i>
                  Fazer nova transação 
                </a>
              </li>
              <li class="nav-item bg-dark border-bottom">
                <a class="nav-link active" style="color:white" href="#">
                  <i class="fa fa-credit-card fa-2x align-middle mr-2"></i>
                  Fazer simulação 
                </a>
              </li>
              <li class="nav-item bg-dark border-bottom">
                <a class="nav-link active" style="color:white" href="#">
                  <i class="fa fa-chart-bar fa-2x align-middle mr-2"></i>
                  Painel do cliente 
                </a>
              </li>
              <li class="nav-item bg-white border-bottom" style="color:black; border-left-width: 3px; border-color: black">
                <a class="nav-link active" style="color:black" href="#">
                  <i class="fa fa-fingerprint fa-2x align-middle mr-2"></i>
                  Meus dados cadastrais
                </a>
              </li>
              <li class="nav-item bg-dark">
                <a class="nav-link active" style="color:white" href="#">
                  <i class="fa fa-cog fa-2x align-middle mr-2"></i>
                  Configurações
                </a>
              </li>
            </ul>
          </div>
        
</template>

<script>
export default {
    name: 'Sidenav'
    // data() {
    //     contador = 1,
    //     side = false
    // },
    // methods: {
    //     mostrar(){
    //         if(contador %2 == 0){
    //             side = true
    //         }
    //         if(contador %2 !=0){
    //             side = false
    //         }
    //     }
    // }
}
</script>

<style src="./style.css" scoped>

</style>
