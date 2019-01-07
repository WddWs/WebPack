<template>
  <div id="app">
    {{text}}
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      text: 'this is tes'
    }
  }
}
</script>

<style scoped>
  #app {
    color: red;
  }
</style>