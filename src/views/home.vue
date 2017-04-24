<template>
    <div class="home">
        <p v-text="msg"></p>
    </div>
</template>
<style class="less" scoped>
    .home{
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        text-align: center;
        line-height: 5rem;
        font-size: 0.5rem;
    }
</style>
<script>
    export default{
        name: 'home',
        data(){
            return{
                msg:'慕思消费者服务系统'
            }
        }
    }
</script>
