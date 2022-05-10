<template>
  <div id="app">
    <tips1></tips1>
  </div>
</template>

<script>
import tips1 from './components/tips/tips1'

export default {
  name: 'App',
  components: {
    tips1
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
