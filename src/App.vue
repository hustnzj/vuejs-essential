<template lang="pug">
  <div id="app">
    <img src="./assets/logo.png">
    h1 Welcome from pug & sass
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  h1{
    color:#42b983;
  }
}
</style>
