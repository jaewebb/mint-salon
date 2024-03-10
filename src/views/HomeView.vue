<script setup lang="ts">
</script>

<template>
  <main>
    <div class="h-screen salon-background">
      <div class="salon-callout w-full h-screen">
        <div class="flex-col bg-black p-10 bg-opacity-60 fade-in">
          <h1 class="text-white mr-5">Hair attuned to you</h1>
          <h2 class="h3 text-white mr-5">We hear you, and we're here for you</h2>
          <h3 class="h4 text-white mr-5">We will help you achieve your hair goals!</h3>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
.salon-background {
  background-image: url('@/assets/images/salon-mint.jpg');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
.salon-callout {
  display: flex;
  align-items: center;
  justify-content: end;
}
</style>