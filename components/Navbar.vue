<template>
  <nav class="bg-white shadow-sm fixed top-0 left-0 right-0 z-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between h-16 items-center">
        <!-- Título como enlace -->
        <NuxtLink to="/"
          class="text-xl font-semibold text-gray-800 hover:text-gold transition duration-300 transform hover:scale-105">
          A y D | 2025
        </NuxtLink>

        <div class="hidden md:flex space-x-6 text-lg font-medium">
          <NuxtLink v-for="link in links" :key="link.label" :to="link.to"
            class="text-gray-700 hover:text-gold group relative transform transition duration-300 ease-in-out hover:scale-105">
            {{ link.label }}
            <!-- Subrayado elegante -->
            <span
              class="absolute left-0 bottom-0 w-0 h-1 bg-gold transition-all duration-300 group-hover:w-full"></span>
          </NuxtLink>
        </div>

        <!-- Burger menu for mobile -->
        <button class="md:hidden focus:outline-none cursor-pointer transform transition duration-300 hover:scale-110"
          @click="isOpen = !isOpen">
          <svg class="w-6 h-6 text-gray-700 transition-transform duration-300 hover:text-gold" fill="none"
            stroke="currentColor" viewBox="0 0 24 24">
            <path :class="{ hidden: isOpen }" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16" class="transition-transform duration-300" />
            <path :class="{ hidden: !isOpen }" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M6 18L18 6M6 6l12 12" class="transition-transform duration-300" />
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile menu -->
    <div v-if="isOpen" class="md:hidden px-4 pb-4 bg-white shadow-md">
      <NuxtLink v-for="link in links" :key="link.label" :to="link.to"
        class="block py-2 ml-2 text-gray-700 hover:text-gold transition duration-300 transform hover:scale-105"
        @click="isOpen = false"> 
        {{ link.label }}
      </NuxtLink>
    </div>
  </nav>
</template>

<script setup>
import { ref } from 'vue'

const isOpen = ref(false)

const links = [
  { label: 'Inicio', to: '/' },
  { label: 'Direcciones', to: '/direcciones' },
  { label: 'Desplazamientos', to: '/desplazamientos' },
  { label: 'Alojamiento', to: '/alojamiento' },
  { label: 'Contacto', to: '/contacto' },
  { label: 'Regalo de boda', to: '/regalo' },
]
</script>

<style scoped>
nav {
  backdrop-filter: blur(6px);
}

.group:hover .group-hover\:w-full {
  width: 100%;
}

.transition-transform {
  transition: transform 0.3s ease;
}

.group:hover span {
  width: 100%;
}
</style>
