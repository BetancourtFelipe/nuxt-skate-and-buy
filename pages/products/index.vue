<template>
  <div>
    <p>Products</p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
definePageMeta({
  layout: 'products',
});
</script>

<style scoped></style>
