<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <vue-lml-learn propData="lml向你问好" />
    </vue-lml-learn>
  </div>
</template>

<script>
import VueLmlLearn from './components/VueLmlLearn.vue'

export default {
  name: 'App',
  components: {
    VueLmlLearn
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
