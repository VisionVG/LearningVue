<script setup lang="ts">
import { useRoute } from 'vue-router';

const route = useRoute();

</script>
<template>
  <div>
    <h1>Project Name</h1>
    <RouterLink to="/">Project {{ route.params?.id }}</RouterLink>
  </div>

  </template>
<style scoped>
</style>

