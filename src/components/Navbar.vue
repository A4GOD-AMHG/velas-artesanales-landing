<template>
  <div class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-[#f0e4e6]">
    <div class="flex justify-between items-center px-6 md:px-12 lg:px-20 py-3 w-full">
      <div class="flex items-center gap-4 text-[#4a3b3e]">
        <div class="size-8 rounded-full bg-primary flex items-center justify-center text-white">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
            stroke="currentColor" class="w-5 h-5">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M15.362 5.214A8.252 8.252 0 0112 21 8.25 8.25 0 016.038 7.048 8.287 8.287 0 009 9.6a8.983 8.983 0 013.361-6.867 8.21 8.21 0 003 2.48z" />
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M12 18a3.75 3.75 0 00.495-7.467 5.99 5.99 0 00-1.925 3.546 5.974 5.974 0 01-2.133-1A3.75 3.75 0 0012 18z" />
          </svg>
        </div>
        <h2 class="text-[#4a3b3e] text-lg font-bold leading-tight tracking-[-0.015em]">Lumina</h2>
      </div>
      <div class="hidden md:flex gap-8 items-center">
        <div class="flex items-center gap-6">
          <a @click.prevent="scrollToSection('#curriculum')" class="text-[#4a3b3e] text-sm font-medium hover:text-primary transition-colors cursor-pointer" href="#curriculum">Plan
            de Estudios</a>
          <a @click.prevent="scrollToSection('#gallery')" class="text-[#4a3b3e] text-sm font-medium hover:text-primary transition-colors cursor-pointer"
            href="#gallery">Galería</a>
          <a @click.prevent="scrollToSection('#about-instructor')" class="text-[#4a3b3e] text-sm font-medium hover:text-primary transition-colors cursor-pointer"
            href="#about-instructor">Instructora</a>
        </div>
        <button
          class="flex min-w-[84px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-5 bg-primary hover:bg-primary-hover transition-colors text-white text-sm font-bold shadow-sm">
          <span class="truncate">Inscríbete Ahora</span>
        </button>
      </div>
      <div class="md:hidden flex items-center">
        <button @click="toggleMenu" class="text-[#4a3b3e]">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
            stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
          </svg>
        </button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const isMenuOpen = ref(false)

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
}

const scrollToSection = (selector: string) => {
  const element = document.querySelector(selector)
  if (element) {
    element.scrollIntoView({ 
      behavior: 'smooth',
      block: 'start'
    })
  }
}
</script>
