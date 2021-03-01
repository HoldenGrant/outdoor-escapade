<template>
    <b-container>
        <b-row>
        <h1>{{ msg }}</h1>
        footer
        </b-row>
    </b-container>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>