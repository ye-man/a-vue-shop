<template>
  <transition name="fade" tag="div">
  <div class="product-page">
    <div class="sidebar-wrap">
      <Sidebar/>
    </div>
    <div class="product-list-wrap">
      <h1>Products</h1>
      <ProductList category="all"/>
      <!-- <router-link to="/cart" exact>Go to Cart</router-link> -->
    </div>
  </div>
</transition>
</template>

<script>
import ProductList from '@/components/ProductList'
import Sidebar from '@/components/Sidebar'

export default {
  name: 'index',
  components: {
    ProductList,
    Sidebar
  }
}
</script>

<style lang="css">
</style>
