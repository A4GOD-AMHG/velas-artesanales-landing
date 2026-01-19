<template>
  <div class="flex justify-center items-center min-h-screen px-4 md:px-10 lg:px-40 py-16 md:py-24 bg-background-light relative overflow-hidden"
    id="pricing">
    <div class="absolute top-0 left-0 w-full h-full opacity-30 pointer-events-none overflow-hidden">
      <div class="absolute top-10 left-10 w-64 h-64 bg-primary rounded-full blur-[100px]"></div>
      <div class="absolute bottom-10 right-10 w-64 h-64 bg-[#e8cc95] rounded-full blur-[100px]"></div>
    </div>
    <div class="layout-content-container flex flex-col md:flex-row max-w-240 flex-1 gap-12 z-10 items-center">
      <div class="flex flex-col gap-6 flex-1">
        <h3 class="text-3xl font-black text-[#4a3b3e] leading-tight">Tu Futuro Creativo Comienza Aquí</h3>
        <p class="text-[#4a3b3e] text-lg leading-relaxed">
          No esperes más para iniciar tu viaje. Únete a una comunidad global de creadores y empieza a diseñar velas que
          cautiven los sentidos y transformen espacios.
        </p>
        <div class="h-px w-full bg-[#ebd5d8]"></div>
        <div class="flex gap-4">
          <div class="flex flex-col">
            <span class="font-bold text-2xl text-[#4a3b3e]">Acceso</span>
            <span class="text-xs text-[#8f6e74] uppercase tracking-wide">De por vida</span>
          </div>
          <div class="w-px bg-[#ebd5d8]"></div>
          <div class="flex flex-col">
            <span class="font-bold text-2xl text-[#4a3b3e]">4.9/5</span>
            <span class="text-xs text-[#8f6e74] uppercase tracking-wide">Valoración</span>
          </div>
        </div>
      </div>
      <div class="flex-1 md:max-w-[400px] w-full">
        <div
          class="bg-white rounded-2xl p-8 shadow-xl border border-[#ebd5d8] flex flex-col gap-6 relative transform md:scale-105 transition-transform">
          <div
            class="absolute top-0 right-0 bg-gold text-white text-xs font-bold px-3 py-1 rounded-bl-xl rounded-tr-xl">
            MEJOR VALOR
          </div>
          <div>
            <h3 class="text-[#4a3b3e] text-2xl font-bold">Pase de Acceso Total</h3>
            <p class="text-[#8f6e74] mt-1">Acceso de por vida a todos los módulos</p>
          </div>
          <div class="flex items-baseline gap-2">
            <span class="text-4xl font-black text-[#4a3b3e]">$149</span>
            <span class="text-lg text-[#8f6e74] line-through decoration-primary decoration-2">$299</span>
          </div>
          <ul class="flex flex-col gap-3">
            <li class="flex items-center gap-3 text-sm text-[#4a3b3e]">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                class="w-5 h-5 text-green-600">
                <path fill-rule="evenodd"
                  d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm13.36-1.814a.75.75 0 10-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 00-1.06 1.06l2.25 2.25a.75.75 0 001.14-.094l3.75-5.25z"
                  clip-rule="evenodd" />
              </svg>
              24 Lecciones en Video HD
            </li>
            <li class="flex items-center gap-3 text-sm text-[#4a3b3e]">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                class="w-5 h-5 text-green-600">
                <path fill-rule="evenodd"
                  d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm13.36-1.814a.75.75 0 10-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 00-1.06 1.06l2.25 2.25a.75.75 0 001.14-.094l3.75-5.25z"
                  clip-rule="evenodd" />
              </svg>
              Manual Digital de 50 Páginas
            </li>
            <li class="flex items-center gap-3 text-sm text-[#4a3b3e]">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                class="w-5 h-5 text-green-600">
                <path fill-rule="evenodd"
                  d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm13.36-1.814a.75.75 0 10-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 00-1.06 1.06l2.25 2.25a.75.75 0 001.14-.094l3.75-5.25z"
                  clip-rule="evenodd" />
              </svg>
              Acceso a Comunidad Privada
            </li>
            <li class="flex items-center gap-3 text-sm text-[#4a3b3e]">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                class="w-5 h-5 text-green-600">
                <path fill-rule="evenodd"
                  d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm13.36-1.814a.75.75 0 10-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 00-1.06 1.06l2.25 2.25a.75.75 0 001.14-.094l3.75-5.25z"
                  clip-rule="evenodd" />
              </svg>
              Certificado de Finalización
            </li>
          </ul>
          <div class="flex flex-col gap-3 mt-2">
            <button
              class="flex w-full items-center justify-center gap-2 rounded-xl h-12 px-5 bg-[#0070BA] hover:bg-[#005ea6] text-white text-base font-bold transition-all shadow-md">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
                <path d="M4.5 3.75a3 3 0 00-3 3v.75h21v-.75a3 3 0 00-3-3h-15z" />
                <path fill-rule="evenodd"
                  d="M22.5 9.75h-21v7.5a3 3 0 003 3h15a3 3 0 003-3v-7.5zm-18 3.75a.75.75 0 01.75-.75h6a.75.75 0 010 1.5h-6a.75.75 0 01-.75-.75zm.75 2.25a.75.75 0 000 1.5h3a.75.75 0 000-1.5h-3z"
                  clip-rule="evenodd" />
              </svg>
              Pagar con PayPal
            </button>
            <p class="text-center text-xs text-[#8f6e74]">
              Garantía de devolución de 30 días • Pago seguro
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
