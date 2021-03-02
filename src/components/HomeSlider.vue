<template>
  <div id="slider-home">
    <VueSlickCarousel :arrows="true" :dots="true" v-bind="settings">
      <div><img alt="Vue logo" src="../assets/logo.png"></div>
      <div><img alt="Vue logo" src="../assets/logo.png"></div>
      <div><img alt="Vue logo" src="../assets/logo.png"></div>
      <div><img alt="Vue logo" src="../assets/logo.png"></div>
    </VueSlickCarousel>
  </div>
</template>
 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'HomeSlider',
    components: { VueSlickCarousel },
    data() {
      return {
        settings: {
        //   arrows: true,
        //   dots: true,
        "autoplay": true,
          "slidesToShow": 3,
            "slidesToScroll": 1,
            "touchThreshold": 5
        },
      }
    },
  }
</script> 

<style lang="sass" scoped>

</style>