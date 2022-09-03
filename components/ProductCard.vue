<template>
  <div class="product-card">
    <div class="image">
      <img :src="product.thumbnail" :alt="product.description" />
    </div>
    <div class="animated-actions">
      <div class="action-wrapper">
        <div></div>
      </div>
    </div>
    <div class="info">
      <p>
        <strong>{{ product.price }} TL</strong>
      </p>
      <p>{{ product.title }}</p>
      <p>{{ product.brand }}</p>
      <p class="rating">Rating: {{ product.rating }}</p>
    </div>
    <div class="actions"></div>
  </div>
</template>

<script>
export default {
  props: { product: Object },
}
</script>
