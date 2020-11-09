<template>
  <div class="home">
    <img alt="My photo" src="../assets/me.jpg">
    <HelloWorld msg="Hien Nguyen"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
