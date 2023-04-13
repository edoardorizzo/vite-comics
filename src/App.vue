<script>
export default {

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

  <main>
    <div class="container">
      <p>__> CONTETNG GOES HERE</p>
    </div>
  </main>

  <footer>
    <div class="container">
      <div class="left_footer">
        <ul>
          <h4>DC COMICS</h4>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <ul>
          <h4>DC</h4>
          <li>Term Of Use</li>
          <li>Privacy Policy</li>
          <li>Add Choice</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent</li>
          <li>CPSC</li>
          <li>Ratings</li>
          <li>Shop Help</li>
        </ul>
        <ul>
          <h4>SITES</h4>
          <li>DC</li>
          <li>Mad Magazine</li>
          <li>DC Kids</li>
          <li>Advertising</li>
        </ul>
        <ul>
          <h4>SHOP DC</h4>
          <li>Shop DC</li>
          <li>Shop Collectibles</li>
        </ul>
      </div>
      <div class="right_footer">
        <div class="logo_footer_container">
          <img src="/img/dc-logo.png" alt="">
        </div>
      </div>
    </div>
  </footer>

  <div class="bottom_bar">
    <div class="container">
      <div class="bottom_bar_left">
        <button>SIGN-UP NOW</button>
      </div>
      <div class="bottom_bar_right">
        <span>FOLLOW US</span>
        <div class="fb_icon icon">
          <img src="/img/footer-facebook.png" alt="">
        </div>
        <div class="tw_icon icon">
          <img src="/img/footer-twitter.png" alt="">
        </div>
        <div class="yt_icon icon">
          <img src="/img/footer-youtube.png" alt="">
        </div>
        <div class="p_icon icon">
          <img src="/img/footer-pinterest.png" alt="">
        </div>
        <div class="pin_icon icon">
          <img src="/img/footer-periscope.png" alt="">
        </div>
      </div>
    </div>

  </div>
</template>

<style lang="scss" scoped>
/* header */
header {
  background-color: white;
  padding: 0.5rem;
}

.container {
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

.navbar a {
  text-decoration: none;
  font-size: 12px;
  margin: 0.5rem;
  color: black;
}

.link_select {
  color: blue;
}

/* header */

/* main */

main {
  background-color: black;
  height: 64px;
}

main p {
  color: white;
}

/* main */

/* footer */

footer {
  background-image: url(/img/footer-bg.jpg);
  background-repeat: no-repeat;
}

.left_footer {
  display: flex;
  padding: 2rem 0;
}

footer ul {
  margin: 0 1rem;
}

footer h4 {
  color: white;
}

footer li {
  color: grey;
  font-size: 12px;
  list-style: none;
  margin: 0.25rem 0;
}

.logo_footer_container {
  width: 300px;
}

.logo_footer_container img {
  width: 100%;
  display: block;
  transform: rotate(-45deg);
  filter: opacity(50%);
}

/* footer */

/* bottom bar */

.bottom_bar {
  background-color: rgb(42, 42, 42);
  padding: 1rem 0;
}

.bottom_bar button {
  padding: 0.25rem;
  border: 1px solid blue;
  background-color: rgb(42, 42, 42);
  color: white;
}

.bottom_bar_right{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.bottom_bar_right span{
  color: blue;
  font-size: 14px;
  margin-right: 8px;
}

.icon{
  width: 16px;
  height: 16px;
  margin: 0 0.25rem;
}

.icon img{
  width: 100%;
}

</style>
