<template>
    <div>
        这是多页的home
    </div>
</template>
<script>
export default {
    name: 'home',
    methods: {

    },
    mounted(){
        console.log(`这是多页的home: ${this.$store.state.myname}`)
    }
}
</script>

