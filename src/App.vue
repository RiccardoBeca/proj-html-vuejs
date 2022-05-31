<template>
  <div>
    <HeaderComp />
    <JumboComp />
    <MainComp />
    <FooterComp />
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import MainComp from './components/MainComp.vue';
import FooterComp from './components/FooterComp.vue';
import JumboComp from './components/JumboComp.vue';

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp,
    JumboComp
  }
}
</script>

<style lang="scss">
@import './assets/style/_vars.scss';
@import './assets/style/_general.scss';
@import './assets/style/_utils.scss';

.svg{
  background-color: lightgrey;
}
</style>
