<template>
    <b-container>
        <b-row>
        <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact-us">Contact Us</router-link>
    </div>
        </b-row>
    </b-container>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>