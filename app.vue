<template>
  <NuxtLayout>
    <template #header> Some header template content. </template>
    <NuxtPage />
    <!-- <NuxtWelcome /> -->
  </NuxtLayout>
</template>

<script setup lang="ts">
useHead({
  title: useAppConfig().title,
});
useDarkMode();
</script>

<style scoped></style>
