<template>
  <div>
    <p>Procuct details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia
      consequuntur, dignissimos nemo officia maxime omnis repellat enim. Beatae
      explicabo blanditiis perferendis incidunt maxime ut alias molestiae, omnis
      corporis quibusdam necessitatibus.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
definePageMeta({
  layout: 'products',
});
</script>

<style scoped></style>
