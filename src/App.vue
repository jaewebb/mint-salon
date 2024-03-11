<script setup lang="ts">
import { RouterView } from 'vue-router'

import AppFooter from '@/components/AppFooter.vue'
import AppHeader from '@/components/AppHeader.vue'
</script>

<template>
  <div class="flex flex-col h-screen justify-between">
    <AppHeader />
    <RouterView class="grow" />
    <AppFooter />
  </div>
</template>

<style>

</style>
