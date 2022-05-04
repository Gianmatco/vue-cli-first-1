<template>
  <div id="app">
    <app-header />
    <main>
      <app-products />
    </main>
    <app-footer />
  </div>
 
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppProducts from './components/AppProducts.vue'
import AppFooter from './components/AppFooter.vue'


export default {
  name: 'App',
  components: {
    AppHeader,
    AppProducts,
    AppFooter
  },
  data() {

  },
  methods:{

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
