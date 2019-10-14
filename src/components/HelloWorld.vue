<template>
  <div class="hello">
    <h1>HelloWorld</h1>
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
<style>
*{
box-sizing: border-box;
margin:0;
padding:0;
}
body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>
