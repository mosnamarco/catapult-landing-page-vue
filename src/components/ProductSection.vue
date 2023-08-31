<script setup lang="ts">
import ProductCard from './ProductCard.vue'
</script>

<template>
  <div class="wrapper">
    <h1>What's hot and pipin!</h1>
    <div class="products">
      <ProductCard>
        <template v-slot:product-image>
          <img src="src/assets/images/bread.jpeg" alt="" />
        </template>
        <template v-slot:product-price> 200 PHP </template>
        <template v-slot:product-name> BREAD BREAD </template>
        <p>This is a fine made bread. Now bread me up baby!</p>
      </ProductCard>
      <ProductCard>
        <template v-slot:product-image>
          <img src="src/assets/images/bread.jpeg" alt="" />
        </template>
        <template v-slot:product-price> 200 PHP </template>
        <template v-slot:product-name> BREAD BREAD </template>
        <p>This is a fine made bread. Now bread me up baby!</p>
      </ProductCard>
      <ProductCard>
        <template v-slot:product-image>
          <img src="src/assets/images/bread.jpeg" alt="" />
        </template>
        <template v-slot:product-price> 200 PHP </template>
        <template v-slot:product-name> BREAD BREAD </template>
        <p>This is a fine made bread. Now bread me up baby!</p>
      </ProductCard>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  background-color: rgba(0, 0, 0, 0.534);
  backdrop-filter: blur(20px);
  min-height: 100vh;
  padding-inline: 10%;
  padding-block: 5%;
  display: flex;
  flex-direction: column;
}
.products {
  display: flex;
  justify-content: space-evenly;
}
img {
  max-width: 200px;
  max-height: 150px;
}
h1 {
  padding-block: 50px;
  font-family: 'Dancing Script', cursive;
}
</style>
