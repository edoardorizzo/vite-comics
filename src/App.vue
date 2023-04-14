<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from './components/SiteMain.vue'
import SiteFooter from './components/SiteFooter.vue'
import SiteBottomBar from './components/SiteBottomBar.vue'
export default {
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
    SiteBottomBar,
  }
}
</script>

<template>

  <SiteHeader></SiteHeader>

  <SiteMain></SiteMain>

  <SiteFooter></SiteFooter>

  <SiteBottomBar></SiteBottomBar>

</template>

<style lang="scss" scoped>
@use './assets/partials/variables' as *;

</style>