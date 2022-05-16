<template>
  <div id="app">
    <HeaderComp />
    <JumbotronComp />
    <MainCardsComp />
    <LinksBeforeFooterComp />
    <FooterComp />
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import JumbotronComp from './components/JumbotronComp.vue'
import MainCardsComp from './components/MainCardsComp.vue'
import LinksBeforeFooterComp from './components/LinksBeforeFooterComp.vue'
import FooterComp from './components/FooterComp.vue'


export default {
  name: 'App',
  components: {
    HeaderComp,
    JumbotronComp,
    MainCardsComp,
    LinksBeforeFooterComp,
    FooterComp,
  }
}
</script>

<style lang="scss">

  @import './assets/style/global';

</style>
