<template>
  <div class="title">
    <h1>{{ msg }}</h1>
 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.title{
  width:100%;
  text-align: center;
}
</style>
