<template>
  <section class="min-h-screen mt-12 px-6 py-16 text-gray-800">
    <h1 class="text-4xl font-serif font-semibold text-center mb-12">Alojamiento</h1>

    <div class="max-w-5xl mx-auto space-y-12">
      <!-- Hotel 1 -->
      <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/hotel1.jpg" alt="Hotel Alfonso XIII" class="absolute inset-0 w-full h-full object-cover" />
        </div>
        <div class="p-6 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-semibold mb-2">Hotel Alfonso XIII</h2>
            <p class="mb-2 text-sm text-gray-600">Precio especial: <strong>220€/noche</strong> (habitación doble con
              desayuno)</p>
            <p class="mb-4 text-sm text-gray-600">Reservas con el código <strong>“BODAELENA”</strong> desde su <a
                href="https://hotel-alfonsoxiii.com" target="_blank"
                class="text-pink-600 hover:text-pink-800 font-medium">web oficial</a> o llamando al <a
                href="tel:+34954123456" class="text-pink-600 hover:text-pink-800 font-medium">+34 954 123 456</a>.</p>
            <p class="text-justify">Uno de los hoteles más emblemáticos de Sevilla, con una ubicación inmejorable junto
              a los Jardines de Murillo. Perfecto para quienes buscan comodidad y lujo.</p>
          </div>
        </div>
      </div>

      <!-- Hotel 2 -->
      <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/hotel2.jpg" alt="Hotel Fernando III" class="absolute inset-0 w-full h-full object-cover" />
        </div>
        <div class="p-6 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-semibold mb-2">Hotel Fernando III</h2>
            <p class="mb-2 text-sm text-gray-600">Precio especial: <strong>120€/noche</strong></p>
            <p class="mb-4 text-sm text-gray-600">Reservas llamando al <a href="tel:+34954111222"
                class="text-pink-600 hover:text-pink-800 font-medium">+34 954 111 222</a> indicando que es para la boda
              de Elena y Javier.</p>
            <p class="text-justify">Hotel moderno y cómodo situado en pleno barrio de Santa Cruz. Cuenta con piscina en
              la azotea y desayuno incluido.</p>
          </div>
        </div>
      </div>

      <!-- Hotel 3 -->
      <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row">
        <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
          <img src="/images/hotel3.jpg" alt="Hotel Petit Palace Santa Cruz"
            class="absolute inset-0 w-full h-full object-cover" />
        </div>
        <div class="p-6 md:w-1/2 flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-semibold mb-2">Petit Palace Santa Cruz</h2>
            <p class="mb-2 text-sm text-gray-600">Precio especial: <strong>95€/noche</strong></p>
            <p class="mb-4 text-sm text-gray-600">Reserva online con el código <strong>“BODA2025”</strong> desde su <a
                href="https://www.petitpalace.com" target="_blank"
                class="text-pink-600 hover:text-pink-800 font-medium">web oficial</a>.</p>
            <p class="text-justify">Alojamiento boutique en una antigua casa señorial andaluza. Muy cerca del lugar de
              la ceremonia.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
