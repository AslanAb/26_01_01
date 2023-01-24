<script>
  export default {
    data () {
      return {
        count: 0
      }
    },
    methods: {
      addCount () {
        this.count ++
      }
    }
    
  }
</script>

<template>
  <span>Count of likes: {{ count }}</span><br>
  <button @click="addCount">Like</button>
</template>

<style scoped>

</style>
