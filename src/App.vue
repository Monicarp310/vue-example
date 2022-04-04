<template>
  <product-card></product-card>
</template>

<script>
import productCard from './components/productCard.vue'

export default {
  name: 'App',
  components: {
    productCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
