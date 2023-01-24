<script>
  export default {
    data () {
      return {
        int: null
      }
    },
    methods: {
      random () {
        this.int = Math.floor(Math.random() * (10 - 1) + 1)
      }
    }
    
  }
</script>

<template>
  <span>Random number from 1 to 10: {{ int }}</span><br>
  <button @click="random">Get random</button>
</template>

<style scoped>

</style>
