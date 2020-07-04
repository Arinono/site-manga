<template>
  <Page>
    <h1 class="text-orange-600">Alors la y a plein de components en dessous ils sont cools</h1>
    <News />
  </Page>
</template>

<script>
  import Page from './shared/Page.vue'

  import Favorites from './listing/Favorites.vue'
  import News from './listing/News.vue'
  import Recommendations from './listing/Recommendations.vue'

  // import Header from shared

  export default {
    name: 'Home',
    components: {
      Favorites,
      News,
      Recommendations,
      Page
    }
  }
</script>

<style scoped>

</style>
