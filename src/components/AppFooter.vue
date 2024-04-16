<template>
  <header class="flex justify-between bg-black text-white p-5 w-full bg-opacity-60 z-50">
    <div><i class="fa-solid fa-leaf mint-leaf"></i> This salon is not real</div>
    <div>&copy; Jae Webb {{ year }}</div>
  </header>
</template>

<script setup lang="ts">
import { computed } from 'vue'

const year = computed(() => {
  const date = new Date()
  return date.getFullYear()
})
</script>

<style scoped></style>
