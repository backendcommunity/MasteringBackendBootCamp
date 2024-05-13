<script lang="ts">
export default {
  name: 'HeroSection'
}
</script>

<template>
  <section class="mb-52 flex flex-col w-full items-center gap-5 mt-5">
    <div class="flex flex-col items-center jusify-center">
      <div class="flex flex-col items-center jusify-center">
        <h2 class="lg:text-6xl text-2xl text-center font-bold">
          What's Inside The Backend Bootcamp?
        </h2>
        <p class="lg:text-2xl py-5 text-center">
          Watch the video below to see the incredible value this cutting-edge training has to offer.
        </p>
      </div>
    </div>
    <div class="lg:w-5/6 w-full border-4 bg-gray-800 shadow-lg rounded-3xl p-2 border-gray-500">
      <img alt="se" class="w-full" src="../assets/vid.svg" />
    </div>
  </section>
</template>