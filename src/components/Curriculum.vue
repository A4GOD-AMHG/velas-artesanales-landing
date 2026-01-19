<template>
  <div class="flex justify-center items-center min-h-screen px-4 md:px-10 lg:px-40 py-12 md:py-20 bg-background-light" id="curriculum">
    <div class="layout-content-container flex flex-col max-w-240 flex-1 gap-10">
      <div class="flex justify-between items-end">
        <h2 class="text-[#4a3b3e] text-3xl md:text-4xl font-black tracking-tight">Plan de Estudios</h2>
        <span class="hidden md:block text-sm font-bold text-primary uppercase tracking-widest">4 Módulos • 24
          Lecciones</span>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="group relative h-64 rounded-xl overflow-hidden cursor-pointer shadow-md">
          <div class="absolute inset-0 bg-cover bg-center transition-transform duration-700 group-hover:scale-110"
            style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuCTqYIcdp_A9BROD1ucKsMOXdL3-cw8dSUGzTpG6qKDuwGnzWUQKCVnqTNdbS1yMoBZVqq6OvzD2rxoqzTEN8lpMFkXRjWKeumD6TRrsw9uMNnHg0s9VOcRMJuGkgKyw4ih3DZwbEuSPKLiEBI-dGXSc0Eb0W0PKzGm-Sz3IaeY5hMnmoo_AOmm5smtQUZLJVhr8YhfAyGDkiY-gcPFDZo63Tukekihi1_-a7XF9nA9pfsoX9xBrPpH1lDCtatE0dGZLC-MJDwhxg8');">
          </div>
          <div class="absolute inset-0 bg-[#2d1b20]/40 group-hover:bg-[#2d1b20]/70 transition-colors duration-300">
          </div>
          <div class="absolute inset-0 p-6 flex flex-col justify-end">
            <div class="transform transition-transform duration-300 translate-y-4 group-hover:translate-y-0">
              <span class="text-primary text-xs font-bold uppercase tracking-wider mb-2 block">Módulo 01</span>
              <h3 class="text-white text-2xl font-bold mb-2">Teoría de la Cera y Mechas</h3>
              <p
                class="text-white/80 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100 max-w-[90%]">
                Comprender diferentes tipos de cera (Soja, Parafina, Cera de Abejas) y elegir el tamaño de mecha
                correcto para evitar túneles.
              </p>
            </div>
          </div>
          <div
            class="absolute top-4 right-4 bg-white/20 backdrop-blur-md rounded-full p-2 text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
            </svg>
          </div>
        </div>
        <div class="group relative h-64 rounded-xl overflow-hidden cursor-pointer shadow-md">
          <div class="absolute inset-0 bg-cover bg-center transition-transform duration-700 group-hover:scale-110"
            style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuCJBO-1W97JRHbyqxE5woqmdh82xTmF-mU3OruIcO8GY1AddWmCxe1Jo90MHNCLRS0wuxREsIScb5eic8bjhVSbILmt7h_AGlUe2UZjFTTeGxZo1rnGZSaJcLFoasGrzgW2RqCKf_jvrRvRh15YFr56gD--31Ps-uc_fP-Dig5mi4IMkfB3VKGF2N6PA8RNB8PnKcMeHtzmTZXw7g9rmH4oTzPvL60LzDsDZhQpR6-5vjf3ZEb0dXkp_JKOtFSNQTozl5b2lFDdT2M');">
          </div>
          <div class="absolute inset-0 bg-[#2d1b20]/40 group-hover:bg-[#2d1b20]/70 transition-colors duration-300">
          </div>
          <div class="absolute inset-0 p-6 flex flex-col justify-end">
            <div class="transform transition-transform duration-300 translate-y-4 group-hover:translate-y-0">
              <span class="text-primary text-xs font-bold uppercase tracking-wider mb-2 block">Módulo 02</span>
              <h3 class="text-white text-2xl font-bold mb-2">La Mezcla del Alquimista</h3>
              <p
                class="text-white/80 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100 max-w-[90%]">
                Mezcla de aceites de fragancia, cálculo de proporciones y comprensión de notas altas, medias y bajas
                para aromas complejos.
              </p>
            </div>
          </div>
          <div
            class="absolute top-4 right-4 bg-white/20 backdrop-blur-md rounded-full p-2 text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
            </svg>
          </div>
        </div>
        <div class="group relative h-64 rounded-xl overflow-hidden cursor-pointer shadow-md">
          <div class="absolute inset-0 bg-cover bg-center transition-transform duration-700 group-hover:scale-110"
            style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuBGTLueR8b5RIZQ6NetF1KbHCiVog0WIIlViFETViyEtlWh0NKAoGsW0LafbOJKTuk3Rk3MB7igA4s2uylyjIOIxYCzM9EfE12zMzB1YoCdSngpEyDQGC7EC6AnXJYJPk2AO7mDF5qcs-TEhRIp80pLUgsxCMKHanLODkreO910nX16WcaGWlH96PT7VOIpcjbEsCiIfq-3xc0yGAtUSz2-_WcNYh-o32mxMrGkgauhlIUAd8zpo0PZtvoJkyPQ-1VggVgx1HWLlq8');">
          </div>
          <div class="absolute inset-0 bg-[#2d1b20]/40 group-hover:bg-[#2d1b20]/70 transition-colors duration-300">
          </div>
          <div class="absolute inset-0 p-6 flex flex-col justify-end">
            <div class="transform transition-transform duration-300 translate-y-4 group-hover:translate-y-0">
              <span class="text-primary text-xs font-bold uppercase tracking-wider mb-2 block">Módulo 03</span>
              <h3 class="text-white text-2xl font-bold mb-2">Estilismo Botánico</h3>
              <p
                class="text-white/80 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100 max-w-[90%]">
                Aplicación segura de flores secas, cristales y pan de oro. Diseño de recipientes y etiquetas para un
                atractivo de alta gama.
              </p>
            </div>
          </div>
          <div
            class="absolute top-4 right-4 bg-white/20 backdrop-blur-md rounded-full p-2 text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
            </svg>
          </div>
        </div>
        <div class="group relative h-64 rounded-xl overflow-hidden cursor-pointer shadow-md">
          <div class="absolute inset-0 bg-cover bg-center transition-transform duration-700 group-hover:scale-110"
            style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDYv7PeLXA-Sv0bDTzAUj1-dxGg2s6iik6IFPC2KsykaSTB7Ix_zymR2NwjfTOvPJ6QGlfW1Ni71gT6H0eqZjD48Ka_4w5vZY_q3NeSZ6MGjl_AqMv6F8BO5uz8E1w1Eu4oPrlIb0Dw4iz3uo6_LsSS6RLhGgsX-PZGSTE5gYzR8Epf25Waz3YoKzDcPnlQQBXXPXxiBOesSOrm_1krh4Bu-UB5dLCISabcEDk_a5q5R-IQuMp1YadF7X04piLHdob0pEixe43mxDM');">
          </div>
          <div class="absolute inset-0 bg-[#2d1b20]/40 group-hover:bg-[#2d1b20]/70 transition-colors duration-300">
          </div>
          <div class="absolute inset-0 p-6 flex flex-col justify-end">
            <div class="transform transition-transform duration-300 translate-y-4 group-hover:translate-y-0">
              <span class="text-primary text-xs font-bold uppercase tracking-wider mb-2 block">Módulo 04</span>
              <h3 class="text-white text-2xl font-bold mb-2">El Negocio de la Luz</h3>
              <p
                class="text-white/80 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100 max-w-[90%]">
                Precios para obtener ganancias, abastecimiento de materiales y comercialización de su colección en
                Instagram y Etsy.
              </p>
            </div>
          </div>
          <div
            class="absolute top-4 right-4 bg-white/20 backdrop-blur-md rounded-full p-2 text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
            </svg>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
