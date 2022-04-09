<template>
  <div id="app">
    <img src="./assets/logo.png">
    <login></login>
  </div>
</template>

<script>
import login from './components/UserLogin.vue'
export default {
  name: 'App',
  components:{
    "login":login
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
