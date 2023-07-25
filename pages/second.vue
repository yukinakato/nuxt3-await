<script setup lang="ts">
await new Promise(resolve => setTimeout(resolve, 3000));
</script>

<template>
  <div>
    Did you find me?
    <NuxtLink to="/">back to /</NuxtLink>
  </div>
</template>
