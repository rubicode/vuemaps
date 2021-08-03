<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <RubiMap msg="Rubi Henjaya"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import RubiMap from './components/RubiMap.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    RubiMap
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
