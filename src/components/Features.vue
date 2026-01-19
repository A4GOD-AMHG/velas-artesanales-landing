<template>
  <div class="flex justify-center items-center min-h-screen px-4 md:px-10 lg:px-40 py-12 md:py-20 bg-white relative">
    <div class="layout-content-container flex flex-col max-w-240 flex-1 gap-12">
      <div class="flex flex-col gap-4 text-center items-center">
        <h2 class="text-[#4a3b3e] text-3xl md:text-4xl font-black tracking-tight">La Experiencia Sensorial</h2>
        <p class="text-[#8f6e74] text-lg max-w-2xl">
          Sumérgete en un mundo de texturas, aromas y luz. Nuestras lecciones de alta definición traen el estudio a tu pantalla.
        </p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="group flex flex-col gap-4 p-6 rounded-xl bg-background-light border border-[#ebd5d8] hover:border-primary/50 transition-colors duration-300">
          <div class="size-12 rounded-full bg-white flex items-center justify-center shadow-sm text-primary group-hover:scale-110 transition-transform">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 h-7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 18v-5.25m0 0a6.01 6.01 0 001.5-.189m-1.5.189a6.01 6.01 0 01-1.5-.189m3.75 7.478a12.06 12.06 0 01-4.5 0m3.75 2.383a14.406 14.406 0 01-3 0M14.25 18v-.192c0-.983.658-1.823 1.508-2.316a7.5 7.5 0 10-7.517 0c.85.493 1.509 1.333 1.509 2.316V18" />
            </svg>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-[#4a3b3e] text-xl font-bold">Derretir y Verter</h3>
            <p class="text-[#8f6e74] text-sm leading-relaxed">
              Domina la ciencia de las temperaturas de la cera. Aprende la técnica de "vertido en frío" para superficies lisas y cremosas siempre.
            </p>
          </div>
        </div>
        <div class="group flex flex-col gap-4 p-6 rounded-xl bg-background-light border border-[#ebd5d8] hover:border-primary/50 transition-colors duration-300">
          <div class="size-12 rounded-full bg-white flex items-center justify-center shadow-sm text-primary group-hover:scale-110 transition-transform">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 h-7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9.813 15.904L9 18.75l-.813-2.846a4.5 4.5 0 00-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 003.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 003.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 00-3.09 3.09zM18.259 8.715L18 9.75l-.259-1.035a3.375 3.375 0 00-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 002.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 002.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 00-2.456 2.456zM16.894 20.567L16.5 21.75l-.394-1.183a2.25 2.25 0 00-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 001.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 001.423 1.423l1.183.394-1.183.394a2.25 2.25 0 00-1.423 1.423z" />
            </svg>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-[#4a3b3e] text-xl font-bold">Teoría del Aroma</h3>
            <p class="text-[#8f6e74] text-sm leading-relaxed">
              Descubre los secretos de las cargas de fragancia y la fijación. Crea perfiles de aroma complejos que llenen una habitación.
            </p>
          </div>
        </div>
        <div class="group flex flex-col gap-4 p-6 rounded-xl bg-background-light border border-[#ebd5d8] hover:border-primary/50 transition-colors duration-300">
          <div class="size-12 rounded-full bg-white flex items-center justify-center shadow-sm text-primary group-hover:scale-110 transition-transform">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 h-7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9.813 15.904L9 18.75l-.813-2.846a4.5 4.5 0 00-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 003.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 003.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 00-3.09 3.09zM18.259 8.715L18 9.75l-.259-1.035a3.375 3.375 0 00-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 002.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 002.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 00-2.456 2.456zM16.894 20.567L16.5 21.75l-.394-1.183a2.25 2.25 0 00-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 001.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 001.423 1.423l1.183.394-1.183.394a2.25 2.25 0 00-1.423 1.423z" />
            </svg>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-[#4a3b3e] text-xl font-bold">Estética Artesanal</h3>
            <p class="text-[#8f6e74] text-sm leading-relaxed">
              Desde arreglos florales secos hasta incrustaciones de cristales, convierte tus velas en obras de arte.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
