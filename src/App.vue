<template>
  <div id="app" >

    <div class="text-center">
      <h1> Stop Flying Blind <span class="fa fa-paper-plane"></span> </h1>
      <br/>
      <h6 class=" text-secondary">A card game to understand and visualize Flight Levels System Architectures in action! </h6>
    </div>

    <Cards msg="Cartoes aqui" />

  </div>

</template>



<script>

import Cards from "./components/Cards.vue"

import "bootstrap/dist/css/bootstrap.css"
import "font-awesome/css/font-awesome.css"
export default {
  name: 'app',
  components: {
      Cards
  }
}
</script>




<style>


</style>
