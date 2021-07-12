<template>
  <div id="app">
    <Header class="header-container"/>
    <Main class="main-container"/>
    <Footer class="footer-container"/>
  </div>
</template>

<script>
import Header from './components/header.vue';
import Main from './components/main.vue';
import Footer from './components/footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
