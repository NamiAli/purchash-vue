<template>
  <div class="app">
      <Topbar />
      <ProductSearch />
      <VerticalNavCarousel />
  </div>
</template>


<script>
  
 import Topbar from './components/Home/Topbar';
 import ProductSearch from './components/Home/ProductSearch'
 import VerticalNavCarousel from './components/Home/VerticalNavCarousel'

  export default {

       components: {
        Topbar,
        ProductSearch,
        VerticalNavCarousel
       }
  }
</script>


<style>
  


</style>