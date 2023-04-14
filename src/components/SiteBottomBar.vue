<script>
    export default {
        name: 'SiteBottomBar',
        data(){
            return{

            }
        }
        
    }
</script>

<template>
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
@use '../assets/partials/variables' as *;
.bottom_bar {
  background-color: $darkgrey;
  padding: 1rem 0;

  button {
    padding: 0.25rem;
    border: 1px solid $blue;
    background-color: $darkgrey;
    color: white;
  }

  .bottom_bar_right {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  span {
    color: $blue;
    font-size: 14px;
    margin-right: 8px;
  }

  .icon {
    width: 16px;
    height: 16px;
    margin: 0 0.25rem;
  }

  img {
    width: 100%;
  }

}
</style>