<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <h1>{{message}}</h1>
  </div>
</template>
<script>
export default {
  data () {
    return {
      userName: 'uno lee',
      message: 'hi good'
    }
  }
}
</script>
<style scoped>
  .text-red {
    color: red;
  }
</style>
