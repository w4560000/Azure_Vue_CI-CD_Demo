<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <br>
    Vue環境 {{envTest}}
    <br>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return { 
      envTest: process.env.VUE_APP_ENVTEST,
    }
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
