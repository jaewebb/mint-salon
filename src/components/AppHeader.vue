<template>
  <header class="flex bg-black text-white p-5 fixed w-screen bg-opacity-60 z-50">
    <span class="logo">Mint Salon</span>
    <nav class="grow text-right">
      <RouterLink
        to="/"
        class="mr-3"
      >
        Home
      </RouterLink>
      <RouterLink
        to="/services"
      >
        Services
      </RouterLink>
      <RouterLink
        to="/contact"
      >
        Contact
      </RouterLink>
    </nav>
  </header>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>