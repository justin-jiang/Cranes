<template>
  <div id="innerApp123">
    <img src="./assets/logo.png">
    <hello></hello>
  </div>
</template>

<script lang='ts'>
import Hello from './components/Hello.vue'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
#innerApp123 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
