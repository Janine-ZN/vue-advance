<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/img/logo.png">
    <Main></Main>
  </div>
</template>

<script>
import Main from './layout/main.vue'

export default {
  name: 'app',
  components: {
    Main
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
