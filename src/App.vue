<template>
  <div id="app">
    <div class="logo">
      <img alt="Vue logo" src="./assets/logo.png">
      <HelloWorld msg="Ciné Files"/>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/Accueil.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
  #logo img{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 40px;
    background-color: white;
    z-index: 9;
    display: none;
  }

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
