<template>
  <div id="app">
    <HeaderContent />
    <MainContent />
    <FooterContent /> 
  </div>
</template>

<script>
import HeaderContent from './components/HeaderContent.vue'
import MainContent from './components/MainContent.vue'
import FooterContent from './components/FooterContent.vue'

export default {
  name: 'App',
  components: {
    HeaderContent,
    MainContent,
    FooterContent
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";

</style>
