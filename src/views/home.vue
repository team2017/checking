<template>
    <div class="home">
        <v-head>
            <div class="left" slot='HL'>
                <img src="../assets/2-back.png">
                <!--<p>返回</p>-->
            </div>
            <div class="mid" slot='HM'>
                <p>我这里是标题党</p>
            </div>
            <div class="right" slot='HR'>
                <img src="../assets/05-home.png">
                <!--<p>首页</p>-->
            </div>
        </v-head>
    </div>
</template>
<style class="less" scoped>

</style>
<script>
    import vHead from '../components/vHead.vue'
    export default{
        name: 'Home',
        components: { vHead }
    }
</script>
