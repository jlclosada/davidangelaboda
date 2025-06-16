<template>
    <section class="min-h-screen mt-12 px-6 py-16 max-w-4xl mx-auto text-gray-800 font-serif">
      <h1 class="text-4xl font-semibold text-center mb-12">Desplazamiento</h1>
  
      <!-- Autobuses -->
      <div class="mb-16 bg-white rounded-2xl shadow-lg p-8">
        <h2 class="text-3xl font-semibold mb-6 text-pink-700">Autobuses</h2>
        <p class="mb-6 italic leading-relaxed text-justify text-gray-700">
          Desde los Jardines de Murillo, saldrán los autobuses que llevarán a la Hacienda tras la ceremonia religiosa en la Iglesia de Santa Cruz (salida programada a las 20:00h). Al terminar la fiesta, los autobuses saldrán de la Hacienda hasta Plaza de Cuba (salida programada a las 06:00h).
        </p>
  
        <!-- <img
          src="/images/esquema_desplazamiento.png"
          alt="Esquema de desplazamiento en autobús"
          class="w-full rounded-xl mb-6 shadow-md"
        /> -->
  
        <div class="flex flex-col gap-4 text-pink-800 font-medium text-lg">
          <a href="https://maps.app.goo.gl/tmXfzziYwGpbEtzRA" target="_blank" class="hover:underline">
            🚏 Jardines de Murillo (Salida)
          </a>
          <a href="https://maps.app.goo.gl/J5YzJypqEREmzUTE6" target="_blank" class="hover:underline">
            🏁 Plaza de Cuba (Llegada)
          </a>
        </div>
      </div>
  
      <!-- Taxis -->
      <div class="bg-white rounded-2xl shadow-lg p-8">
        <h2 class="text-3xl font-semibold mb-6 text-pink-700">Taxis</h2>
        <p class="mb-6 italic leading-relaxed text-justify text-gray-700">
          Para traslados en horarios diferentes, os dejamos los siguientes contactos de Taxis:
        </p>
  
        <ul class="space-y-4 text-gray-800">
          <li>
            <strong>Teléfono de parada:</strong><br />
            <a href="tel:+34954141359" class="text-pink-700 font-medium hover:underline">+34 954 14 13 59</a>
          </li>
          <li>
            <strong>José Requena Muñoz:</strong><br />
            <a href="tel:+34619718514" class="text-pink-700 font-medium hover:underline">+34 619 71 85 14</a>
          </li>
          <li>
            <strong>Félix José García Barrios:</strong><br />
            <a href="tel:+34639767842" class="text-pink-700 font-medium hover:underline">+34 639 76 78 42</a>
          </li>
        </ul>
      </div>
    </section>
  </template>
  
  <script setup>
  // No es necesario código extra por ahora
  </script>
  
  <style scoped>
  /* Para usar la fuente Baskerville con prioridad */
  section {
    font-family: 'Libre Baskerville', serif;
  }
  </style>
  