<template>
  <footer>
    <b-container>
        <b-row>
          <b-col class="text-lg-left text-sm-center">footer</b-col>
          <!-- <b-col cols="12" md="auto">Variable width content</b-col> -->
          <b-col lg="4" sm="12">3 of 3</b-col>
        
        </b-row>
    </b-container>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>