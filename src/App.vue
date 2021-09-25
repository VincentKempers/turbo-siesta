<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <the-canvas />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TheCanvas from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TheCanvas
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

    body {
        margin: 0;
        overflow: hidden;
    }

    canvas {
        width: 100vw;
        height: 100vh;
    }
</style>
