<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

import AppHeader from '@/components/AppHeader.vue'
</script>

<template>
  <AppHeader />

  <RouterView />
</template>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

h1, .h1 {
  font-size: 2rem;
}

h2, .h2 {
  font-size: 1.8rem;
}

h3, .h3 {
  font-size: 1.6rem;
}

h4, .h4 {
  font-size: 1.4rem;
}

h5, .h5 {
  font-size: 1.2rem;
}

h6, .h6 {
  font-size: 1rem;
}
</style>
