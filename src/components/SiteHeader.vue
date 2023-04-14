<script>
    export default {
        name:'SiteHeader',
        data(){
            return{

            }
        }
    }
</script>

<template>
    <header>
    <div class="container">
      <div class="left_header">
        <img src="/img/dc-logo.png" alt="">
      </div>
      <div class="right_header">
        <div class="navbar">
          <a class="link_select" href="#">CHARACTERS</a>
          <a href="#">COMICS</a>
          <a href="#">MOVIES</a>
          <a href="#">TV</a>
          <a href="#">GAMES</a>
          <a href="#">COLLECTIONS</a>
          <a href="#">VIDEOS</a>
          <a href="#">FANS</a>
          <a href="#">NEWS</a>
          <a href="#">SHOP</a>
        </div>
      </div>
    </div>
  </header>
</template>



<style lang="scss" scoped>

header {
  background-color: white;
  padding: 0.5rem;

  .left_header {
    width: 32px;
    height: 32px;
  }

  img {
    width: 100%;
  }

  a {
    text-decoration: none;
    font-size: 12px;
    font-weight: bold;
    margin: 0.5rem;
    color: black;
  }

  .link_select {
    color: blue;
  }
}

</style>