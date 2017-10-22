<template>
  <div id="app">
    <product-list-one :products="products"></product-list-one>
    <product-list-two :products="products"></product-list-two>
  </div>
</template>

<script>
  import ProductListOne from './components/ProductListOne.vue'
  import ProductListTwo from './components/ProductListTwo.vue'

  export default {
    name: 'app',
    components: {
      ProductListOne,
      ProductListTwo
    },
    data() {
      return {}
    }
  }
</script>

<style lang="scss">
  body {
    font-family: Ubuntu;
    color: #555;
  }
</style>
