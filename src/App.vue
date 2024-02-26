<template>
  <div id="app">
    <HighChart></HighChart>
  </div>
</template>

<script>
import HighChart from './components/HighChart.vue';

export default {
  name: 'App',
  components: {
    HighChart
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
