<template>
  <div class="min-h-screen flex flex-col">
    <NavBar />
    <main class="flex-grow">
      <router-view></router-view>
    </main>
    <FooterBar />
  </div>
</template>

<script>
import NavBar from './NavBar.vue'
import FooterBar from './FooterBar.vue'

export default {
  name: 'MainLayout',
  components: {
    NavBar,
    FooterBar
  }
}
</script> 