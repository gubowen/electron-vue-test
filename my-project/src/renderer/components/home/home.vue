<template>
    <div id="home">{{home}}</div>
</template>
<script>
    export default {
        name: 'home',
        data(){
            return {
                home: "这是我的首页！"
            }
        },
        mounted() {
        },
        methods: {}
    }
</script>
<style lang="css" rel="stylesheet/css">
    #home{
        background: #fff;
    }
</style>