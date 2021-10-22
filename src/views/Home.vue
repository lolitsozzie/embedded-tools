<template>
  <div class="home">
    <img alt="Vue logo" class="logo" src="../assets/logo.png">
    <HelloWorld msg="welcome to ozzies embedded toolkit"/>
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

<style scoped>
.logo {
  max-width: 60%;
}
</style>
