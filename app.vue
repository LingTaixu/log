<template>
  <NuxtLayout>
    <NuxtPage />
    <!-- <NuxtWelcome /> -->
  </NuxtLayout>
</template>

<script setup lang="ts">
useHead({
  title: useAppConfig().title,
});
</script>

<style scoped></style>
