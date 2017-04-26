<template>
    <div class="vHead">
        <slot name='HL'></slot>
        <slot name='HM'></slot>
        <slot name='HR'></slot>
    </div>
</template>
<style lang="less" scoped>
    .vHead{
        position: relative;
        width: 100%;
        height: 1.2rem;
        background: #aaa;
        .left,.right {
            position: absolute;
            top: 0;
            width: 1.3rem;
            height: 1.2rem;
            p {
                line-height: 1.2rem;
                font-size: 0.48rem;
                color: #eee;
            }
            img {
                width: 0.5rem;
                height: auto;
            }
        }
        .left{
            left: 0;
            p{ text-align: right;}
            img{
                padding: 0.35rem 0.55rem 0.35rem 0.25rem;
            }
        }
        .right{
            right: 0;
            p{ text-align: left;}
            img{
                padding: 0.35rem 0.25rem 0.35rem 0.55rem;
            }
        }
        .mid{
            width: 74%;
            height: 1.2rem;
            margin: 0 auto;
            line-height: 1.2rem;
            text-align: center;
            p{
                font-size: 0.48rem;
                color: #eee;
            }
        }

    }
</style>
<script>
    export default{
        name: 'vHead'
    }
</script>
