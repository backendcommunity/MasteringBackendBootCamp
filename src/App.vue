<script lang="ts">
import HeroSection from './components/HeroSection.vue'
import OutlineSection from './components/OutlineSection.vue'
import FirstSection from './components/FirstSection.vue'
import CountDown from './components/CountDown.vue'
import BecomeSection from './components/BecomeSection.vue'
import WhatYouLearn from './components/WhatYouLearn.vue'
import LimitedSlot from './components/LimitedSlot.vue'
import LearnSection from './components/LearnSection.vue'
import CertificateSecttion from './components/CertificateSecttion.vue'
import AdvantageSection from './components/AdvantageSection.vue'
import TestimonialsSection from './components/TestimonialSection.vue'
import MeetInstructor from './components/MeetInstructor.vue'
import FooterSection from './components/FooterSection.vue'
import BonusSection from './components/BonusSection.vue'
import FaqSection from './components/FaqSection.vue'

export default {
  components: {
    OutlineSection,
    FirstSection,
    HeroSection,
    CountDown,
    BecomeSection,
    WhatYouLearn,
    LimitedSlot,
    LearnSection,
    CertificateSecttion,
    AdvantageSection,
    TestimonialsSection,
    MeetInstructor,
    FooterSection,
    BonusSection,
    FaqSection
  }
}
</script>
<template>
  <main class="bg-gray-100">
    <section class="container mx-auto w-full lg:px-16 py-10 px-5">
      <header class="pb-5 w-full">
        <img alt="logo" src="./assets/logo.svg" />
      </header>
      <div class="py-6">
        <hero-section />

        <count-down />
        <first-section />

        <become-section />
        <WhatYouLearn />
        <limited-slot />
        <learn-section />
        <certificate-secttion />
        <limited-slot />

        <outline-section />

        <advantage-section />

        <bonus-section />
        <testimonials-section />
        <meet-instructor />
        <faq-section />
        <count-down />
      </div>
      <footer-section />
    </section>
  </main>
</template>




<style scoped></style>
