<template>
  <div id="app">
    {{titolo}} 
   
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
  data(){ 
    return {
      titolo: 'Mio titolo',
    
    }
  },
  methods:{

  }
}
</script>

<style >

</style>
