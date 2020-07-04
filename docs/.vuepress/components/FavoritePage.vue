<template>
  <Page>
    <h2>Favoris :</h2>
    <Favorites />
  </Page>
</template>

<script>
  import Page from './shared/Page.vue'

  import Favorites from './listing/Favorites.vue'

  export default {
    name: 'FavoritePage',
    components: {
      Favorites,
      Page
    }
  }
</script>

<style scoped>

</style>
