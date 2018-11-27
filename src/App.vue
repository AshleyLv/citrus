<template>
  <div id="app">
    <top-nav></top-nav>
    <router-view/>
    <div class="base">base</div>
  </div>
</template>
<script>
    import topNav from '@/components/nav.vue'
    export default {
        name: 'home',
        components: {
            topNav
        }
    }
</script>
<style lang="scss">
@import "assets/css/material-icons.min.css";
#app {
  font-family: 'Microsoft Yahei' !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

</style>
