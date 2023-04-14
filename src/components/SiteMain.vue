<script>
import ComicCard from './ComicCard.vue'
export default {
  components:
    ComicCard,
  name: 'SiteMain',
  data() {
    return {


    }
  }
}
</script>

<template>
  <main>
    <div class="container">
      
      <ComicCard v-for="(series, index) in comics" :src="comic[index].thumb" :alt="comic[index].series" ></ComicCard>

    </div>
  </main>
</template>



<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

main {
  background-color: $black;
  height: 64px;

  p {
    color: white;
  }
}
</style>