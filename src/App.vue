<template>
  <Clock/>
</template>

<script>
import Clock from './components/Clock.vue'

export default {
  name: 'App',
  components: {
    Clock
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
  margin: 0;
}
body{
  margin: 0;
  -webkit-app-region: drag;
}
</style>
