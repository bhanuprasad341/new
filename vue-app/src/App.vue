<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <hello msg="Welcome to Your Vue.js App"/>
    <med msg="Welcome to Your Vue.js App"/>
    <vid msg="Welcome to Your Vue.js App"/>
    <health msg="Welcome to Your Vue.js App"/>
    <test msg="Welcome to Your Vue.js App"/>
    <feed msg="Welcome to Your Vue.js App"/>
    <foot msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import hello from './components/hello.vue'
import Med from './components/med.vue'
import Vid from './components/vid.vue'
import Health from './components/health.vue'
import Test from './components/test.vue'
import Feed from './components/feed.vue'
import Foot from './components/foot.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    hello,
    Med,
    Vid,
    Health,
    Test,
    Feed,
    Foot
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

