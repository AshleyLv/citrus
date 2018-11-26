<template>
    <mu-appbar style="width: 100%;" color="primary" :textColor="navColor" :color="color">
        <mu-button icon slot="left">
            <mu-icon value="menu"></mu-icon>
        </mu-button>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>


        <mu-button flat slot="right">LOGIN</mu-button>
    </mu-appbar>
</template>
<script>
    export default {
        name: 'nav',
        data(){
            return {
                navColor:'#fff',
                color:'#ccc'
            }
        }
    }
</script>
<style lang="scss">

</style>