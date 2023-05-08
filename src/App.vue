<template class="Border">
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
 
  
  <Teleport to="#footer">

    <weatherbox />
    <FooterComp />
  </Teleport>


</template>

<script>



import weatherbox from './components/weatherbox.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    weatherbox,
    FooterComp

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
