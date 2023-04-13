<script>
export default {

}
</script>

<template>
  <SiteHeader></SiteHeader>
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

  <main></main>

  <footer></footer>
</template>

<style lang="scss" scoped>
/* header */
header {
  background-color: white;
  padding: 0.5rem;
}

.container{
  margin: 0 64px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.left_header {
  width: 32px;
  height: 32px;
}

.left_header img {
  width: 100%;
}

.navbar a{
  text-decoration: none;
  font-size: 12px;
  margin: 0.5rem;
  color: black;
}
.link_select{
  color: blue;
}

/* header */


</style>
