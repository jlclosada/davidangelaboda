<template>
  <section class="min-h-screen mt-12 px-6 py-16 text-gray-800">
    <h1 class="text-4xl font-serif font-semibold text-center mb-12">Direcciones</h1>

    <div class="grid gap-12 max-w-5xl mx-auto">
      <!-- Tarjeta Iglesia -->
      <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/iglesia.jpg" alt="Iglesia de Santa Cruz de Sevilla"
            class="absolute inset-0 w-full h-full object-cover" />
        </div>
        <div class="p-6 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-semibold mb-4">Iglesia de Santa Cruz de Sevilla</h2>
            <p class="mb-4 text-justify">
              En esta iglesia, se realizará la ceremonia a las <strong>18:15h</strong>. Se recomienda venir andando o en
              taxi/VTC.
              Si vienes en coche propio, debes tener en cuenta que hay un parking de pago cerca (Cano y Cueto), pero es
              pequeño y se llena rápidamente. A 10 minutos andando, también se encuentra el parking Avenida Roma.
            </p>
          </div>
          <a href="https://maps.app.goo.gl/dnGpLdXythGkGMno7" target="_blank"
            class="mt-4 inline-flex items-center gap-x-2 w-fit pr-5 bg-pink-100 text-pink-700 px-4 py-2 rounded-full font-medium shadow-md transition transform hover:scale-105 hover:bg-pink-200 hover:shadow-lg">
            📍 <span>Ver en Google Maps</span>
          </a>
        </div>
      </div>

      <!-- Tarjeta Hacienda -->
      <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/hacienda.jpg" alt="Hacienda Atalaya Alta"
            class="absolute inset-0 w-full h-full object-cover" />
        </div>
        <div class="p-6 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-semibold mb-4">Hacienda Atalaya Alta</h2>
            <p class="mb-4 text-justify">
              Aquí tienes la dirección de la Hacienda donde se celebrará el banquete. ¡Guárdatela para no perderte!
              Esta Hacienda cuenta con un amplio parking en la entrada, donde podrás aparcar gratuitamente sin
              problemas.
            </p>
          </div>
          <a href="https://maps.app.goo.gl/3smD4AbUJEP5WYcRA" target="_blank"
            class="mt-4 inline-flex items-center gap-x-2 w-fit pr-5 bg-pink-100 text-pink-700 px-4 py-2 rounded-full font-medium shadow-md transition transform hover:scale-105 hover:bg-pink-200 hover:shadow-lg">
            📍 <span>Ver en Google Maps</span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
