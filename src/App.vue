<template>
  <div id="app">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
    <img alt="China logo" src="./assets/china.png">

<!--    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <ImOk></ImOk>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorldrld.vue'
import ImOk from "@/components/ImOk";

export default {
  name: 'App',
  components: {
    // HelloWorld,
    ImOk,

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
