<template>
  <HeaderVue/>
  <ContentHeader/>
  <MainContent/>
</template>

<script>
import HeaderVue from './components/HeaderVue.vue'
import ContentHeader from './components/ContentHeader.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    HeaderVue,
    ContentHeader,
    MainContent
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
  text-align: center;
}

body {
  margin-top: 0;
  padding: 0;
}
</style>
