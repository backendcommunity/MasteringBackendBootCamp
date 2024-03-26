<script lang="ts">
import HeroSection from './components/HeroSection.vue';
import FirstSection from './components/FirstSection.vue';
import CountDown from './components/CountDown.vue';
import BecomeSection from './components/BecomeSection.vue';
import WhatYouLearn from './components/WhatYouLearn.vue';
import LimitedSlot from './components/LimitedSlot.vue';
import LearnSection from './components/LearnSection.vue';
import CertificateSecttion from './components/CertificateSecttion.vue';
import AdvantageSection from './components/AdvantageSection.vue';
import TestimonialsSection from './components/TestimonialSection.vue';




export default {
  components: { HeroSection, FirstSection, CountDown, BecomeSection, WhatYouLearn, LimitedSlot, LearnSection, CertificateSecttion, AdvantageSection, TestimonialsSection, }
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
    <become-section />
    <WhatYouLearn />
    <limited-slot />
    <learn-section />
    <certificate-secttion />
    <limited-slot />
    <advantage-section />
    <testimonials-section />
  </main>
</template>




<style scoped></style>
