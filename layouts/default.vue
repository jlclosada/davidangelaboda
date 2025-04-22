<template>
  <div class="min-h-screen bg-ivory text-gray-800 font-serif flex flex-col">
    <Navbar />

    <main class="flex-1">
      <slot />
    </main>

    <Footer />
  </div>
</template>

<script setup>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'
</script>
