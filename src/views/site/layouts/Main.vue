<template>
  <div class="wrapper bg-secondary">
    <Header />
    <BreadCrumb />
    <div class="content">
      <slot />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from './Header.vue'
import BreadCrumb from './BreadCrumb.vue'
import Footer from './Footer.vue'
export default {
    components: {
      Header, BreadCrumb, Footer
    },
}
</script>

<style lang="scss" module>
@import "@/assets/site/sass/app.scss";
</style>