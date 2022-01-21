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
//  text-shadow: -1px -1px 0 #2f3437, 1px -1px 0 #2f3437, -1px 1px 0 #2f3437, 1px 1px 0 #2f3437;
</script>

<style scoped>
h1{
  color: #f4f6f8;
  background: #2f3437;
  border-radius: 25px;
  maring: 0;
  padding: 5px;
}
</style>
