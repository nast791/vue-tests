<template>
  <section class="header">
    <div class="container">
      <router-link :to="'/'" :exact="true" active-class="link-active">
        <img src="../../../assets/img/logo.png" alt="" class="logo">
      </router-link>
      <button class="entry-btn" type="button">Войти</button>
    </div>
  </section>
</template>

<script>
  export default {
    name: "Header"
  }
</script>

<style lang="scss" scoped>
  @import "header.scss";
</style>