<template>
  <div class="last-news">
    <h3>Dernières sorties :</h3>
    <div class="slider">
      <MangaCard
        v-for="(card, idx) in cards"
        :manga="card.manga"
        :title="card.title"
        :chapter="card.chapter"
        :team="card.team"
        :bgImg="card.bgImg"
      />
    </div>
  </div>
</template>

<script>
  import MangaCard from '../shared/MangaCard.vue'

  export default {
    name: 'News',
    components: {
      MangaCard
    },
    data: () => ({
      cards: [
        {
          manga: 'One Piece',
          title: 'Ma bible',
          chapter: '984',
          team: 'Scantrad.fr',
          bgImg: '../../public/mangas/test.png'
        },
        {
          manga: 'Raba the mules',
          title: 'Fuck Japscan',
          chapter: '8',
          team: 'Furyo Squad',
          bgImg: '../../public/mangas/test.png'
        },
        {
          manga: 'Jigokuraku',
          title: 'Fuck Japscan',
          chapter: '101',
          team: 'Kangaryu-team',
          bgImg: '../../public/mangas/test.png'
        }
      ]
    })
  }
</script>

<style scoped>

</style>
