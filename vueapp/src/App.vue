<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Atom Vue.js App"/> 
    <center>Hello </center>
    <i class="fab fa-facebook-square"></i>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
  export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

// <script>
// import '@fortawesome/fontawesome-free/css/all.css' // Ensure you are using css-loader
// import Vue from 'vue'
// import Vuetify from 'vuetify/lib'

// Vue.use(Vuetify)

// export default new Vuetify({
//   icons: {
//     iconfont: 'fa',
//   },
// })
// </script>

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
