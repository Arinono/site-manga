<template>
  <div class="manga-card">
    <div class="manga-card-bg"></div>
    <div class="infos">
      <h4>{{ manga }}</h4>
      <span class="manga-card-title">{{ title }}</span>
      <span class="manga-card-chap">{{ chapter }}</span>
      <span class="manga-card-team">{{ team }}</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'MangaCard',
    props: {
      manga: {
        type: String,
        required: true
      },
      title: {
        type: String,
        required: true
      },
      chapter: {
        type: String,
        required: true
      },
      team: {
        type: String,
        required: true
      },
      bgImg: {
        type: String,
        required: true
      }
    }
  }
</script>

<style scoped>

</style>
