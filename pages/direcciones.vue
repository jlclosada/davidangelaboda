<template>
  <section class="min-h-screen mt-12 px-6 py-16 text-gray-800 bg-gradient-to-br from-pink-50 via-white to-orange-50">
    <h1 class="text-5xl text-center mb-16 text-pink-900 drop-shadow-sm">Direcciones</h1>

    <div class="grid gap-20 max-w-5xl mx-auto">
      <!-- Iglesia -->
      <div class="bg-white/80 backdrop-blur-sm rounded-3xl shadow-xl overflow-hidden flex flex-col md:flex-row transition hover:shadow-2xl hover:scale-[1.01] duration-300">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/iglesia.jpg" alt="Iglesia de Santa Cruz de Sevilla"
            class="absolute inset-0 w-full h-full object-cover transition duration-300 hover:scale-105" />
        </div>
        <div class="p-8 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-3xl font-serif font-semibold mb-4 text-pink-800">Iglesia de Santa Cruz de Sevilla</h2>
            <p class="mb-4 text-justify text-gray-700 leading-relaxed">
              La ceremonia será a las <strong>18:15h</strong>. Te recomendamos venir andando o en taxi/VTC.
              Si vienes en coche, hay un parking de pago cerca (Cano y Cueto), aunque suele llenarse rápido.
              También está el parking Avenida Roma, a 10 minutos a pie.
            </p>
          </div>
          <a
            href="https://maps.app.goo.gl/dnGpLdXythGkGMno7"
            target="_blank"
            class="mt-6 self-start relative inline-flex items-center gap-x-2 px-5 py-2.5 text-pink-800 bg-pink-100 rounded-full font-medium shadow transition duration-300 hover:bg-pink-200 hover:shadow-lg group"
          >
            📍 <span class="z-10 relative">Ver en Google Maps</span>
            <span class="absolute inset-0 rounded-full bg-white opacity-0 group-hover:opacity-20 transition duration-300"></span>
          </a>
        </div>
      </div>

      <!-- Hacienda -->
      <div class="bg-white/80 backdrop-blur-sm rounded-3xl shadow-xl overflow-hidden flex flex-col md:flex-row transition hover:shadow-2xl hover:scale-[1.01] duration-300">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/atalaya.png" alt="Hacienda Atalaya Alta"
            class="absolute inset-0 w-full h-full object-cover transition duration-300 hover:scale-105" />
        </div>
        <div class="p-8 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-3xl font-serif font-semibold mb-4 text-pink-800">Hacienda Atalaya Alta</h2>
            <p class="mb-4 text-justify text-gray-700 leading-relaxed">
              Aquí se celebrará el banquete. La Hacienda cuenta con un amplio parking gratuito en la entrada, así que
              no tendrás problema para aparcar si vienes en coche.
            </p>
          </div>
          <a
            href="https://maps.app.goo.gl/3smD4AbUJEP5WYcRA"
            target="_blank"
            class="mt-6 self-start relative inline-flex items-center gap-x-2 px-5 py-2.5 text-pink-800 bg-pink-100 rounded-full font-medium shadow transition duration-300 hover:bg-pink-200 hover:shadow-lg group"
          >
            📍 <span class="z-10 relative">Ver en Google Maps</span>
            <span class="absolute inset-0 rounded-full bg-white opacity-0 group-hover:opacity-20 transition duration-300"></span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
