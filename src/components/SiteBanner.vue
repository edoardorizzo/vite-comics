<script>
    export default {
        name: 'SiteBanner',
        data (){
            return {

            }
        }
    }
</script>

<template>
    <div class="banner">
    <div class="banner_section">
      <div class="image_container">
        <img src="/img/buy-comics-digital-comics.png" alt="">
      </div>
      <span>Lorem Ipsum</span>
    </div>
    <div class="banner_section">
      <div class="image_container">
        <img src="/img/buy-comics-merchandise.png" alt="">
      </div>
      <span>Lorem Ipsum</span>
    </div>
    <div class="banner_section">
      <div class="image_container">
        <img src="/img/buy-comics-shop-locator.png" alt="">
      </div>
      <span>Lorem Ipsum</span>
    </div>
    <div class="banner_section">
      <div class="image_container">
        <img src="/img/buy-comics-subscriptions.png" alt="">
      </div>
      <span>Lorem Ipsum</span>
    </div>
    <div class="banner_section">
      <div class="image_container">
        <img src="/img/buy-dc-power-visa.svg" alt="">
      </div>
      <span>Lorem Ipsum</span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

.banner {
  height: 80px;
  background-color: $blue;
  display: flex;
  justify-content: space-around;
  align-items: center;

  .banner_section{
    display: flex;
    align-items: center;
  }


  .image_container {
    height: 32px;
    width: 24px;
    display: flex;
    margin: 0.5rem;
  }

  img {
    width: 100%;
  }

  span {
    color: $white;
    font-size: 12px;
    display: inline-block;
  }
}

</style>