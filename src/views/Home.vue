<template>
  <div>
    <HeroSection />
    <PresentationSection />
    <ChefWordsSection />
  </div>
</template>

<script>
import HeroSection from '@/components/sections/HeroSection.vue'
import PresentationSection from '@/components/sections/PresentationSection.vue'
import ChefWordsSection from '@/components/sections/ChefWordsSection.vue'

export default {
  name: 'Home',
  components: {
    HeroSection,
    PresentationSection,
    ChefWordsSection
  }
}
</script> 