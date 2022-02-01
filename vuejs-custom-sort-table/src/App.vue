<template>
  <div id="app">
    <sortable />
  </div>
</template>

<script>
import sortable from './components/sortable.vue'

export default {
  name: 'App',
  components: {
    sortable
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
