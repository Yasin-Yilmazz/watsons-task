<template>
  <div class="featured">
    <div class="title">
      <div class="divider"></div>
      <strong>Featured products</strong>
      <div class="divider"></div>
    </div>
    <div class="product-list">
      <ProductCard
        v-for="product in products"
        :product="product"
        :key="product.id"
      />
    </div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  data() {
    return {
      products: null,
    }
  },
  created() {
    axios
      .get(`https://dummyjson.com/products/`)
      .then((response) => {
        this.products = response.data.products.slice(0, 4)
        console.log(response.data.products.slice(0, 4))
      })
      .catch((e) => {
        console.log(e)
      })
  },
}
</script>
