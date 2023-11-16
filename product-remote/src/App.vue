<script setup lang="ts">
import ProductList from './components/ProductList.vue';

const numberOfRowsToRender = 5;
</script>

<template>
  <div>
    <ProductList :numberOfRowsToRender="numberOfRowsToRender" />
  </div>
</template>

<style scoped>
h1 {
  text-align: center;
}
</style>
