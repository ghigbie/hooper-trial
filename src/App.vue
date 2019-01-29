<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HooperTest/>
  </div>
</template>

<script>
import HooperTest from './components/HooperTest.vue'

export default {
  name: 'app',
  components: {
    HooperTest
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
