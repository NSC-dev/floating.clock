<template>
    <h1>{{ this.time }}</h1>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      time: null
    }
  },
  methods: {
    setTime(){
      setInterval(() => {
      this.time = new Date().toLocaleTimeString()
      }, 1000)
    }
  },
  mounted() {
    this.setTime()
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  maring: 0;
  padding: 0;
}
</style>
