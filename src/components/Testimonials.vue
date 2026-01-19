<template>
  <div class="flex justify-center items-center min-h-screen px-4 md:px-10 lg:px-40 py-12 md:py-20 bg-background-light relative overflow-hidden">
    <div class="absolute top-10 right-0 w-100 h-100 smoke-wisp translate-x-1/2 opacity-30 pointer-events-none">
    </div>
    <div class="layout-content-container flex flex-col max-w-240 flex-1 gap-12 z-10">
      <div class="text-center">
        <h2 class="text-[#4a3b3e] text-3xl font-bold tracking-tight mb-2">Testimonios</h2>
        <p class="text-[#8f6e74]">Historias de éxito de nuestra comunidad.</p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-xl shadow-sm border border-[#ebd5d8] flex flex-col gap-4">
          <div class="flex items-center gap-1 text-secondary">
            <svg v-for="i in 5" :key="i" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
              class="w-4 h-4">
              <path fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z"
                clip-rule="evenodd" />
            </svg>
          </div>
          <p class="text-[#4a3b3e] text-sm leading-relaxed italic">"¡Increíble curso! Nunca pensé que podría hacer velas
            tan hermosas desde mi primera lección. La comunidad es súper solidaria."</p>
          <div class="flex items-center gap-3 mt-auto">
            <div class="w-10 h-10 rounded-full bg-cover bg-center"
              style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuBK3TGmQ7XvkS8slbeHuqjhZgUoUqSidh94I_QLCIrpGyTp3ikBcD2MshW6JsiGSM1t4Ov11hsHXc3-0O_gxmcjFPy1TYD6EcDJl0kmKtVJ75TEHGpZWPZmVhyOVKPNsavCkdQdwYdnn8siegATudElUFkOzxANwdzNk9181utvOiiVA9_9BJWfhkB92QIu4eotwDPJItwR7WPy9lZfezYbUWhFQeCq_we7j1BiOJqFhrGNBjFQj_beEmfGKNHgbHYMWGoSRU-y7AI');">
            </div>
            <div>
              <h4 class="text-sm font-bold text-[#4a3b3e]">Sofía M.</h4>
              <p class="text-xs text-[#8f6e74]">Estudiante</p>
            </div>
          </div>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm border border-[#ebd5d8] flex flex-col gap-4">
          <div class="flex items-center gap-1 text-secondary">
            <svg v-for="i in 5" :key="i" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
              class="w-4 h-4">
              <path fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z"
                clip-rule="evenodd" />
            </svg>
          </div>
          <p class="text-[#4a3b3e] text-sm leading-relaxed italic">"La sección de teoría del aroma cambió todo para mi
            pequeño negocio. Ahora mis velas huelen tan bien como se ven."</p>
          <div class="flex items-center gap-3 mt-auto">
            <div class="w-10 h-10 rounded-full bg-cover bg-center"
              style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuBZjZuncMKa_gPZEqIFWgfwg4q9ciHASCulZy1AcN-OSWoq4q6PPzlu2xh8x-kAWYExjXj3xKTmQuCbHFKulLrWT3uc3I2_H9wameC576GhTpG-wAthYbtgqo_tPEe2YxG5kKtTusocs_wz85q5Rs043-cDPNINUpAm7JujcvEnQ5ZKULuIUGV5VHEZ1O2h9za3FhYqlw_4sfWfESO1MSA8gXexe9M8-7UhLiH7hnU5-U1C18M6T4JEoNlwWiTZ-ngefdAyaGy4M2s');">
            </div>
            <div>
              <h4 class="text-sm font-bold text-[#4a3b3e]">Carlos R.</h4>
              <p class="text-xs text-[#8f6e74]">Dueño de Tienda</p>
            </div>
          </div>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm border border-[#ebd5d8] flex flex-col gap-4">
          <div class="flex items-center gap-1 text-secondary">
            <svg v-for="i in 5" :key="i" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
              class="w-4 h-4">
              <path fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z"
                clip-rule="evenodd" />
            </svg>
          </div>
          <p class="text-[#4a3b3e] text-sm leading-relaxed italic">"Elena explica todo con tanta pasión y claridad. Vale
            cada centavo por el manual y los videos de alta calidad."</p>
          <div class="flex items-center gap-3 mt-auto">
            <div class="w-10 h-10 rounded-full bg-cover bg-center"
              style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuAUpH4PKpLUclYpQtWYZKeV7maBWLWLMf9CkNXWTPza2Z_3nh47h2iBiYChw6vscCfYtY9KHD6v_JtE4PJjPlqzVGhHK7MsMP76COZSEAr-V6zqQmjolNgBdg9Q_H_RWriKGqXgDcgwTUnI-3GBmHw0IzsGrX1tQ7s-pbgXNOR7JsLbyHie4ZpK3kwKi-kYyOJ2lMPdl2xhN63vbVD7F7asYqlMXhKGdcUJ8xMdHmHtSj0trSjB_Y919RCfRrDb54I-lnUG2Ghnfjg');">
            </div>
            <div>
              <h4 class="text-sm font-bold text-[#4a3b3e]">Valentina L.</h4>
              <p class="text-xs text-[#8f6e74]">Hobbyista</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.smoke-wisp {
  background: radial-gradient(ellipse at center, rgba(255, 255, 255, 0.4) 0%, rgba(255, 255, 255, 0) 70%);
  filter: blur(20px);
  opacity: 0.6;
}
</style>
