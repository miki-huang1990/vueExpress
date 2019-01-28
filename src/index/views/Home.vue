<template>
  <div style="font-size: 30px;">
    这个是单页面的主页home.vue
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {
  },
  mounted() {
    console.log(`这个是单页面的主页home: ${this.$store.state.myname}`)
  }
}
</script>