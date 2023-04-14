<script>
    export default {
        name:'SiteFooter',
        data(){
            return{
                

            }
        }
    }
</script>

<template>
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
          <img src="/img/dc-logo-bg.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>



<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

footer {
  background-image: url(/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;

  .left_footer {
    display: flex;
  }

  ul {
    margin: 0 1rem;
  }

  h4 {
    color: $white;
  }

  li {
    color: $grey;
    font-size: 12px;
    list-style: none;
    margin: 0.25rem 0;
  }

  .logo_footer_container {
    width: 300px;
  }

  img {
    width: 100%;
    display: block;
  }

}

</style>