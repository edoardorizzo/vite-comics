<script>
    export default {
        name: 'SiteHero',
    }
</script>

<template>
    <div class="hero">
    <div class="hero_tag"> CURRENT SERIES </div>
  </div> 
</template>



<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

.hero {
  background-image: url(/img/jumbotron.jpg);
  height: 240px;
  background-size: cover;
  position: relative;
}

.hero_tag{
  background-color: $blue;
  padding: 0.25rem;
  width: 120px;
  text-align: center;
  font-weight: bold;
  color: $white;
  position: absolute;
  top: 95%;
  left: 5%;
}
</style>