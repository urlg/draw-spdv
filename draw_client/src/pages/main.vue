<template>
  <div class="main">
        {{name}}
  </div>
</template>

<script>
export default {
  data () {
    return {
      name: 'HelloWorld',
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .main{
        background-color: bisque;
        height: 100%;
        width: 100%;
    }
</style>
