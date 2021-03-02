<template>
  <div class="home">
    <HomeSlider/>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import HomeSlider from '@/components/HomeSlider.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    HomeSlider
  }
}
</script>
