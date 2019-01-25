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
    console.log('这个是单页面的主页about.vue')
    //console.log(`这个是默认页面的主页：${this.$store.state.myname}`)
  }
}
</script>