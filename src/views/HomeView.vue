<script setup lang="ts">
import ProductSection from '../components/ProductSection.vue'
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
  <ProductSection />
</template>

<style scoped>
main {
  height: calc(100vh - 100px);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
</style>
