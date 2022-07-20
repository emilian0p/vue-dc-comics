<template>
  <div id="app">
    <HeaderContent />
    <JumbotronContent />
    <ProductContainer />
    <MainContent />
    <FooterContent /> 
  </div>
</template>

<script>
import HeaderContent from './components/HeaderContent.vue';
import MainContent from './components/MainContent.vue';
import FooterContent from './components/FooterContent.vue';
import ProductContainer from './components/ProductContainer.vue';
import JumbotronContent from './components/JumbotronContent.vue';

export default {
  name: 'App',
  components: {
    HeaderContent,
    JumbotronContent,
    ProductContainer,
    MainContent,
    FooterContent
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";

</style>
