<template>
  <component :is="currentLayout"></component>
</template>

<script>
  export default {
    data: () => ({
      currentLayout: 'MainLayout'
    }),
    components: {
      MainLayout: () => import('./components/layouts/MainLayout/MainLayout'),
    }
  }
</script>

<style lang="scss">
  @import "assets/global.scss";
</style>
