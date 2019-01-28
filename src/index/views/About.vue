<template>
  <div style="font-size: 30px;">
    这个是单页面的主页about.vue
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {
  },
  mounted() {
    console.log(`这个是单页面的主页about：${this.$store.state.myname}`)
  }
}
</script>