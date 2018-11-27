<template>
    <mu-appbar style="width: 100%;" color="primary" :textColor="navColor" :color="color">
        <mu-button flat slot="left">
            <mu-icon value="build"></mu-icon>
            <span class="title">balabala</span>
        </mu-button>
        <!--<mu-button flat slot="left">-->
        <router-link to="/">Home</router-link>
        <!--</mu-button>-->
        <!--<mu-button flat slot="left">-->
        <router-link to="/about">About</router-link>
        <!--</mu-button>-->


        <mu-button flat slot="right">LOGIN</mu-button>
    </mu-appbar>
</template>
<script>
    export default {
        name: 'nav',
        data(){
            return {
                navColor:'#fff',
                color:'#0094bb'
            }
        }
    }
</script>
<style lang="scss">
    a{
        color: #ffffff !important;
        display: inline-block;
        padding: 0 30px;
        &:hover{
            background: #1ea1c3;
            cursor: pointer;
        }
    }
    .title{
        font-size: 18px;
    }
</style>