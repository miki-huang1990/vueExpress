<template>
    <div>
        这是多页的about
    </div>
</template>
<script>
export default {
    name: 'about',
    methods: {

    },
    mounted(){
        console.log(`这是多页的about: ${this.$store.state.myname}`)
    }
}
</script>

