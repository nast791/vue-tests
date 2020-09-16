<template>
  <section class="footer">
    <div class="container">
      <p class="copyright">&copy; Все права защищены. Тесты {{year}}</p>
    </div>
  </section>
</template>

<script>
  export default {
    name: "Footer",
    computed: {
      year() {
        return new Date().getFullYear();
      }
    }
  }
</script>

<style lang="scss" scoped>
  @import "footer.scss";
</style>