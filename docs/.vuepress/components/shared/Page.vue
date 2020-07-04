<template>
  <div>
    <Navbar />

    <slot />

    <Footer />
  </div>
</template>

<script>

  // import Navbar from './Navbar.vue'
  import Navbar from '@vuepress/theme-default/components/Navbar.vue'
  import Footer from './Footer.vue'

  export default {
    name: 'Page',
    components: {
      Navbar,
      Footer
    }
  }
</script>

<style scoped>

  .navbar {
    position: static;
  }

</style>
