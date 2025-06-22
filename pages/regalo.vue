<template>
  <section class="min-h-screen mt-12 px-6 py-16 text-gray-800">
    <h1 class="text-4xl font-serif font-semibold text-center mb-12">Regalo de boda</h1>

    <div class="max-w-3xl mx-auto text-lg leading-relaxed space-y-6">
      <div class="flex justify-center mb-8">
        <img src="/images/regalos.jpg" alt="Regalos" class="max-w-full w-96 rounded-lg shadow-md" />
      </div>

      <p class="text-justify">
        Sabemos que lo importante es compartir este día con vosotros, y vuestra presencia ya es el mejor regalo. Pero si os apetece tener un detalle con nosotros, os lo intentaremos poner fácil: Ya tenemos un juego de sartenes, una air fryer, y platos, cuencos y fuentes que no combinan entre sí: todo lo que necesita una pareja joven como nosotros para sobrevivir. Por eso, si queréis echarnos una mano para empezar esta nueva aventura, os dejamos los datos de nuestra cuenta bancaria, donde podréis contribuir a nuestro fondo de <em>“aventuras, muebles como los que tienen nuestros padres y que no existen en Ikea, y otros conceptos que aún están en el aire...”</em>
      </p>

      <div class="bg-pink-50 border border-pink-200 rounded-2xl shadow-md p-6 mt-8 text-center">
        <h2 class="text-xl font-semibold mb-4 text-pink-700">Datos bancarios</h2>
        <div class="flex items-center justify-center gap-3 font-mono text-sm text-gray-700">
          <span>{{ account }}</span>

          <div class="relative group">
            <button @click="copyToClipboard"
              class="p-2 bg-gray-300 rounded-full hover:bg-gray-400 transition relative cursor-pointer"
              aria-label="Copiar IBAN">
              📋
            </button>
            <span v-if="!copied"
              class="absolute -top-8 left-1/2 transform -translate-x-1/2 bg-gray-800 text-white text-xs px-2 py-1 rounded opacity-0 group-hover:opacity-100 transition">
              Copiar
            </span>
          </div>

          <span v-if="copied" class="text-green-600 text-sm ml-2">¡Copiado!</span>
        </div>

        <p class="mt-2 text-sm text-gray-500 italic">
          Por favor, indicad vuestro nombre en el concepto
        </p>

      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';
const account = 'ES60 0239 0806 7737 6558 4325';

// Estado para mostrar el mensaje "Copiado"
const copied = ref(false);

// Función para copiar el IBAN al portapapeles
const copyToClipboard = async () => {
  try {
    await navigator.clipboard.writeText(account);
    copied.value = true;

    // Ocultar el mensaje después de 2 segundos
    setTimeout(() => {
      copied.value = false;
    }, 2000);
  } catch (err) {
    console.error("Error al copiar el IBAN", err);
  }
};
</script>