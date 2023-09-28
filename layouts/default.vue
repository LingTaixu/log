<template>
  <div>
    <header class="lg:hidden">
      <slot name="header"> Default header content </slot>
    </header>
    <slot />
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
