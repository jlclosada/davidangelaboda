<template>
  <section class="min-h-screen mt-12 px-6 py-16 text-gray-800">
    <h1 class="text-4xl font-serif font-semibold text-center mb-12">Alojamiento</h1>

    <div class="max-w-5xl mx-auto space-y-12">
      <!-- Opciones con descuentos -->
      <div>
        <h2 class="text-3xl font-semibold mb-6 border-b-2 border-pink-600 pb-2">Opciones con descuentos</h2>

        <!-- Hotel Meliã Sevilla -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel2.jpg" alt="Hotel Meliã Sevilla" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Meliã Sevilla</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio:</strong> 210€/noche 2 pax con desayuno</p>
              <p class="mb-2 text-sm text-gray-600">Reserva online en el enlace <strong>Boda Ángela y David</strong></p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 21 min (1,5 km) a la iglesia, 21 min (1,5 km) desde Plaza de Cuba.</p>
              <p class="text-justify">Hotel moderno de 4 estrellas ubicado en el centro de Sevilla, frente a la Plaza de España y junto al Parque de María Luisa. Ofrece habitaciones elegantes, piscina al aire libre y una excelente conexión con los principales puntos de interés de la ciudad.</p>
            </div>
          </div>
        </div>

        <!-- Hotel Tayko Sevilla -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel1.jpg" alt="Hotel Tayko Sevilla" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Tayko Sevilla</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio:</strong> desde €/noche 2 pax (mínimo 2 noches)</p>
              <p class="mb-2 text-sm text-gray-600">Reserva online en la web <a href="https://taykohotels.com/sevilla/" target="_blank" class="text-pink-600 hover:text-pink-800 font-medium">taykohotels.com/sevilla/</a> con el código <strong>David&amp;Angela</strong> (seleccionando tarifa flexible).</p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 11 min (800 m) a la iglesia, 7 min (450 m) desde Plaza de Cuba.</p>
              <p class="text-justify">Hotel boutique de 4 estrellas, ubicado en el corazón de Sevilla, junto a la Puerta de Jerez. Su ubicación es la más ideal para los invitados. Ofrece habitaciones elegantes con techos altos y grandes ventanales, además de un restaurante de cocina local y un ambiente moderno y acogedor. Plazas muy limitadas.</p>
            </div>
          </div>
        </div>

        <!-- Hotel Fernando III -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel3.jpg" alt="Hotel Fernando III" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Fernando III</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio:</strong> desde €/noche 2 pax</p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 3 min (200 m) a la iglesia, 20 min (1,4 km) desde Plaza de Cuba.</p>
              <p class="text-justify">Elegante hotel de 4 estrellas situado en el corazón del barrio de Santa Cruz, a pocos pasos de la iglesia de Santa Cruz. Ofrece habitaciones modernas y confortables, una terraza en la azotea con piscina y vistas panorámicas de la ciudad, y un restaurante que sirve cocina andaluza y europea. Excelente opción para los invitados que deseen disfrutar de Sevilla durante el fin de semana.</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Otras opciones sin descuento -->
      <div>
        <h2 class="text-3xl font-semibold mb-6 border-b-2 border-pink-600 pb-2">Otras opciones sin descuento</h2>

        <!-- Hotel Eurostars Guadalquivir -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel2.jpg" alt="Hotel Eurostars Guadalquivir" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Eurostars Guadalquivir</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio:</strong> desde 151€/noche 2 pax</p>
              <p class="mb-2 text-sm text-gray-600">Reserva online en <a href="https://www.eurostarshotels.com/eurostars-guadalquivir.html" target="_blank" class="text-pink-600 hover:text-pink-800 font-medium">eurostarshotels.com</a></p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 23 min (1,7 km) a la iglesia, 6 min (450 m) desde Plaza de Cuba.</p>
              <p class="text-justify">Moderno hotel de 4 estrellas situado entre los barrios de Triana y Los Remedios. Ofrece habitaciones elegantes, gimnasio con sauna y baño de vapor, desayuno buffet y aparcamiento privado. Su ubicación estratégica lo convierte en una opción cómoda y bien comunicada para los invitados que deseen explorar la ciudad.</p>
            </div>
          </div>
        </div>

        <!-- Hotel Alcázar -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel1.jpg" alt="Hotel Alcázar" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Alcázar</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio aprox.:</strong> desde 138€/noche 2 pax</p>
              <p class="mb-2 text-sm text-gray-600">Reserva online en su web: <a href="https://www.hotelalcazar.com/es/" target="_blank" class="text-pink-600 hover:text-pink-800 font-medium">hotelalcazar.com</a></p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 9 min (650 m) a la iglesia, 17 min (1,2 km) desde Plaza de Cuba.</p>
              <p class="text-justify">Alojamiento de 3 estrellas ubicado en el centro histórico de Sevilla, frente al barrio de Santa Cruz y los Jardines de Murillo. Ofrece habitaciones renovadas con vistas a monumentos como la Catedral y el Real Alcázar.</p>
            </div>
          </div>
        </div>

        <!-- Hotel Monte Carmelo -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel1.jpg" alt="Hotel Monte Carmelo" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Monte Carmelo</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio aprox.:</strong> desde 135€/noche 2 pax (mínimo 2 noches)</p>
              <p class="mb-2 text-sm text-gray-600">Reserva online en su web: <a href="https://www.hotel-montecarmelo.com/" target="_blank" class="text-pink-600 hover:text-pink-800 font-medium">hotel-montecarmelo.com</a></p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 23 min (1,6 km) a la iglesia, 6 min (400 m) desde Plaza de Cuba.</p>
              <p class="text-justify">Alojamiento de 4 estrellas situado en el barrio de Los Remedios, a solo 10 minutos a pie del centro histórico de Sevilla. Ofrece habitaciones modernas y confortables, desayuno buffet y parking privado, siendo una opción ideal para los invitados que deseen pasar el fin de semana completo en Sevilla.</p>
            </div>
          </div>
        </div>

        <!-- Hotel Murillo -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col md:flex-row mb-8">
          <div class="relative w-full md:w-1/2 aspect-video overflow-hidden">
            <img src="/images/hotel3.jpg" alt="Hotel Murillo" class="absolute inset-0 w-full h-full object-cover" />
          </div>
          <div class="p-6 md:w-1/2 flex flex-col justify-between">
            <div>
              <h3 class="text-2xl font-semibold mb-2">Hotel Murillo</h3>
              <p class="mb-2 text-sm text-gray-600"><strong>Precio aprox.:</strong> desde 180€/noche 2 pax o 311€/2 noches 2 pax</p>
              <p class="mb-2 text-sm text-gray-600">Reserva online en <a href="https://www.hotelmurillo.com/" target="_blank" class="text-pink-600 hover:text-pink-800 font-medium">hotelmurillo.com</a> o llamando al teléfono <a href="tel:+34954216095" class="text-pink-600 hover:text-pink-800 font-medium">954 216 095</a>.</p>
              <p class="mb-4 text-sm text-gray-600">Distancia a pie: 3 min (210 m) a la iglesia, 16 min (1,2 km) desde Plaza de Cuba.</p>
              <p class="text-justify">Alojamiento de 2 estrellas ubicado en el corazón del Barrio de Santa Cruz, a pocos pasos de la Catedral, el Alcázar y la Iglesia de Santa Cruz, donde se celebrará la boda. Ofrece habitaciones cómodas, una terraza con vistas y un ambiente acogedor, ideal para los invitados que deseen alojarse en el centro histórico de Sevilla.</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Nota adicional -->
      <p class="mt-12 max-w-3xl mx-auto text-center text-gray-600 italic">
        Además de estas, existen muchas otras opciones de hoteles y apartamentos turísticos por la zona que podréis buscar a través de aplicaciones como Google Maps, Booking o Airbnb, para encontrar la opción que mejor se adapte a vuestras necesidades.
      </p>
    </div>
  </section>
</template>
