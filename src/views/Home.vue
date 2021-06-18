<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" width="300px">
    <HelloWorld msg="Welcome to Your Vue.js Deploy Working"/>
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
