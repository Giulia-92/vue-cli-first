<template>
  <div id="app">
    <NuovoTitolo />
  </div>
</template>

<script>
import NuovoTitolo from './components/NuovoTitolo.vue'

export default {
  name: 'App',
  components: {
    NuovoTitolo
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
