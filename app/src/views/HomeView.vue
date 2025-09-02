<template>
  <card />
</template>

<script setup>
  import { defineAsyncComponent } from 'vue';

  const card = defineAsyncComponent(() =>
    import('@/Components/CardContainer.vue'));
</script>
