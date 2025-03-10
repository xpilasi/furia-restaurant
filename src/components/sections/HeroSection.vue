<template>
  <section class="relative h-screen bg-cover bg-center" style="background-image: url('/path-to-your-image.jpg')">
    <div class="absolute inset-0 bg-black/50"></div>
    <div class="relative container mx-auto px-6 h-full flex items-center justify-center">
      <div class="text-center text-white">
        <h1 class="text-5xl font-bold mb-4">Nombre del Restaurante</h1>
        <p class="text-xl mb-8">La mejor experiencia culinaria</p>
        <button class="bg-white text-black px-8 py-3 rounded-full hover:bg-gray-100">
          Reservar ahora
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script> 