<template>
  <div id="app">
    <Padre />
  </div>
</template>

<script>
import Padre from './components/Padre.vue'

export default {
  name: 'app',
  components: {
    Padre,
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
