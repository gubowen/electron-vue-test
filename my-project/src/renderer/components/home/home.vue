<template>
    <div id="home">
        <div>{{home}}</div>
        <div>{{$store.state.Counter.main}}</div>
    </div>
</template>
<script>
    export default {
        name: 'home',
        data(){
            return {
                home: "这是我的首页2！"
            }
        },
        mounted() {
        },
        methods: {}
    }
</script>
<style lang="scss" rel="stylesheet/css">
    #home {
        background: #fff;
    }
</style>