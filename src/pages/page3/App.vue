<template>
  <div id="app">
    <p>page 3</p>
    <img src="../../assets/logo.png">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from '../../components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
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
