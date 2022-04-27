<template>
  <div id="app">
    <Head />
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Head from './components/head.vue'
import $ from 'jquery'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Head
  },
  mounted () {
    $('img').click(function () {
      $(this).hide(1000)
    })
  }
}
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
