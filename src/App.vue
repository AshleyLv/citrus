<template>
  <div id="app">
    <top-nav></top-nav>
    <router-view/>
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
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

</style>
