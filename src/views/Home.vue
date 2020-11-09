<template>
  <div class="home">
    <img alt="My photo" src="../assets/me.jpg">
    <Home msg="Hien Nguyen"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from '@/components/Home.vue'

export default {
  name: 'Home',
  components: {
    Home
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  max-width: 20%;
  height: auto;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>