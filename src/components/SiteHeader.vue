<script>
    export default {
        name:'SiteHeader',
        data(){
            return{
                menu: [
                    {
                        text: 'CHARACTERS',
                        href: '#',
                        current: true,
                    },
                    {
                        text: 'COMICS',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'MOVIES',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'TV',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'GAMES',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'COLLECTIONS',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'VIDEOS',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'FANS',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'NEWS',
                        href: '#',
                        current: false,
                    },
                    {
                        text: 'SHOP',
                        href: '#',
                        current: false,
                    },
                ]

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
          <a v-for="(text, index) in menu" class="link_select" href="#">{{ menu[index].text }}</a>
        </div>
      </div>
    </div>
  </header>
</template>



<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

header {
  background-color: $white;
  padding: 0.5rem;

  .left_header {
    width: 56px;
    height: 56px;
  }

  img {
    width: 100%;
  }

  a {
    text-decoration: none;
    font-size: 16px;
    font-weight: bold;
    margin: 0.5rem;
    color: $black;

    &:hover{
      color: $blue;
    }
  }
}

</style>