<template>
  <div id="app">
    <p>首页</p>
    <Header></Header>
  </div>
</template>

<script>
import HelloWorld from '../../components/HelloWorld'
import Header from '../../components/Header.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header
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
