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
  font-family: Roboto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin: 0;
}
body{
  margin: 0;
  -webkit-app-region: drag;
  overflow: hidden;
}
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 100;
  font-display: swap;
  src: url(./assets/Roboto.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
</style>
