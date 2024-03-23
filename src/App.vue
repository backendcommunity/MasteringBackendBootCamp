<script lang="ts">
import HeroSection from './components/HeroSection.vue'

export default {
  components: { HeroSection },

}

</script>
<template>
  <header class="w-full flex justify-center p-5  ">
    <img alt="logo" class=" w-96" src="./assets/logo.svg" />
  </header>

  <main class="p-16">
    <hero-section />
  </main>
</template>

<style scoped></style>
