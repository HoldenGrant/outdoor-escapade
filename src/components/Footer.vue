<template>
  <footer>
    <b-container>
        <b-row>
          <b-col class="text-lg-left text-sm-center">Copyright © {{currentYear}} <router-link to="/">OUTDOOR ESCAPADE</router-link>. All rights reserved.</b-col>
          <!-- <b-col cols="12" md="auto">Variable width content</b-col> -->
          <b-col lg="4" sm="12">
            asdasd
          </b-col>
        
        </b-row>
    </b-container>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {
      currentYear: new Date().getFullYear(), // 2020
    };
  }
}
</script>