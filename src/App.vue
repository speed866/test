<template>
  <div id="app">
    <h1>jesse</h1>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <DoSomething></DoSomething>
<<<<<<< HEAD
    <h1>jesse</h1>
=======
    <p>other change</p>
>>>>>>> origin/main
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import DoSomething from './components/DoSomething.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    DoSomething
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
