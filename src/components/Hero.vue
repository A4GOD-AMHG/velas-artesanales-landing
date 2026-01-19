<template>
  <div
    class="relative flex flex-col items-center justify-center min-h-screen w-full px-4 pt-4 md:px-10 overflow-hidden">
    <div
      class="absolute top-0 right-0 w-[500px] h-[500px] rose-petal translate-x-1/3 -translate-y-1/3 opacity-60 pointer-events-none animate-pulse">
    </div>
    <div
      class="absolute bottom-0 left-0 w-[600px] h-[600px] rose-petal -translate-x-1/3 translate-y-1/3 opacity-40 pointer-events-none">
    </div>
    <div class="absolute top-1/4 left-10 w-[300px] h-[300px] smoke-wisp opacity-30 pointer-events-none"></div>
    <div class="flex flex-col w-full max-w-7xl relative z-10 animate-fade-in-up">
      <div class="rounded-xl overflow-hidden relative shadow-2xl">
        <div class="absolute inset-0 bg-gradient-to-t from-[#2d1b20]/60 via-[#2d1b20]/20 to-transparent z-10"></div>
        <div class="h-[600px] md:h-[700px] bg-cover bg-center"
          style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuCyEE8g7jN4QSizr4tuxpJn923JSoHH6ozv8IhDeDZ5WAj5EKrm0CY8-Ex4trvYdeO_yNrDh8l6R52GzAsrPdbExgCdE0TSHYWtS0f3IgtAV3Dm_ClYw-s-a0vtw4UiYhm2czXKRCKemTdbj7Y4_I2_JQUwiE2BdPKH1WESaXMeZmejbt7nxJ2ub6fryL47CMBlHX0w-rQ4esEiHSVGrugUpSMIYHtH-w9839lov2j1bImDDoNhV7rpO23nsIRW7KGGa0CvPLGBtCE');">
        </div>
        <div class="absolute inset-0 z-20 flex flex-col items-center justify-center text-center p-6 md:p-12 gap-6">
          <span
            class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/20 backdrop-blur-sm border border-white/30 text-white text-xs font-bold uppercase tracking-wider">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M15.362 5.214A8.252 8.252 0 0112 21 8.25 8.25 0 016.038 7.048 8.287 8.287 0 009 9.6a8.983 8.983 0 013.361-6.867 8.21 8.21 0 003 2.48z" />
            </svg>
            Curso Online Premium
          </span>
          <h1
            class="text-white text-4xl md:text-6xl lg:text-7xl font-black leading-tight tracking-tight text-shadow max-w-4xl">
            Domina el Arte de las <br /> <span class="text-gold">Velas Aromáticas</span>
          </h1>
          <p class="text-white/90 text-base md:text-xl font-normal max-w-xl leading-relaxed text-shadow">
            Un viaje inmersivo hacia la fabricación de velas artesanales. Aprende a mezclar fragancias, verter
            perfectamente y crear tu propia marca boutique.
          </p>
          <div class="flex flex-col sm:flex-row gap-4 mt-4">
            <button
              @click="scrollToPricing"
              class="flex items-center justify-center h-12 px-8 bg-gold hover:bg-gold-hover transition-all transform hover:scale-105 rounded-xl text-white text-base font-bold shadow-lg gap-2">
              <span>Empezar a Aprender</span>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="w-5 h-5">
                <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const scrollToPricing = () => {
  const element = document.querySelector('#pricing')
  if (element) {
    element.scrollIntoView({ 
      behavior: 'smooth',
      block: 'center'
    })
  }
}
</script>

<style scoped>
.rose-petal {
  background: radial-gradient(circle at center, rgba(214, 140, 150, 0.25) 0%, rgba(255, 245, 247, 0) 70%);
  border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
  transform: rotate(15deg);
}

.smoke-wisp {
  background: radial-gradient(ellipse at center, rgba(255, 255, 255, 0.4) 0%, rgba(255, 255, 255, 0) 70%);
  filter: blur(20px);
  opacity: 0.6;
}

.text-shadow {
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

@keyframes fade-in-up {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in-up {
  animation: fade-in-up 0.8s ease-out;
}
</style>
