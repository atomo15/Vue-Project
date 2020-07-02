<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Atom Vue.js App"/> 
    <center>
    <a onclick="show()">
    <i class="fa fa-facebook-official fa-6" aria-hidden="true"></i>
    </a>
    </center>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
  export default {
  name: 'App',
  components: {
    HelloWorld
  }}
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
