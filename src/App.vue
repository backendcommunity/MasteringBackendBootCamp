<script lang="ts">
import HeroSection from './components/HeroSection.vue';
import FirstSection from './components/FirstSection.vue';
import CountDown from './components/CountDown.vue';



export default {
  components: { HeroSection, FirstSection, CountDown }
}
</script>
<template>
  <header class="w-full flex justify-center p-5  bg-gray-100 ">
    <img alt="logo" class=" lg:w-80 w-52" src="./assets/logo.svg" />
  </header>
  <main class="lg:p-16 p-5  bg-gray-100">
    <hero-section />
    <first-section />
    <count-down />

  </main>
</template>




<style scoped></style>
