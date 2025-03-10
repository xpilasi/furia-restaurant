<template>
  <nav class="bg-white shadow-md">
    <div class="container mx-auto px-6 py-4">
      <div class="flex justify-between items-center">
        <div class="text-xl font-bold">Logo</div>
        <div class="space-x-4">
          <router-link to="/" class="hover:text-gray-600">Inicio</router-link>
          <router-link to="/menu" class="hover:text-gray-600">Menú</router-link>
          <router-link to="/contacto" class="hover:text-gray-600">Contacto</router-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script> 