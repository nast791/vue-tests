<template>
  <div class="wrapper">
    <Header/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
  export default {
    name: "MainLayout",
    components: {
      Header: () => import('../../others/Header/Header'),
      Footer: () => import('../../others/Footer/Footer'),
    }
  }
</script>

<style scoped>

</style>