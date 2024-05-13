<script lang="ts">
export default {
  name: 'LimitedSlot'
}
</script>
<template>
  <section class="mb-52 lg:grid flex flex-col gap-10 grid-cols-2 lg:p-10 rounded-2xl bg-white">
    <div class="col-span-1 hidden lg:flex">
      <img alt="logo" class="lg:w-96 w-52" src="../assets/ball.svg" />
    </div>

    <div class="col-span-1 flex flex-col gap-5 p-5 lg:p-10 items-center rounded-xl border">
      <div class="inline">
        <p class="bg-red-500 text-white lg:text-sm text-xs rounded-full p-3 lg:px-9 inline">
          LIMITED SLOTS AVAILABLE
        </p>
      </div>
      <p class="lg:text-6xl font-bold text-center">Get Started <span> Now</span></p>
      <p class="text-center text-gray-600">
        Join The <span class="text-black text-lg font-bold"> Backend Bootcamp</span> today to
        transform your career in the booming Backend industry. Claim your
        <span class="text-black text-lg font-bold">50% off </span>launch discount for
        <span class="text-black text-lg font-bold">30 days only</span>.
      </p>

      <p class="text-5xl relative lg:text-8xl font-extrabold">
        $500
        <span class="absolute text-gray-500 decoration-red-500 line-through text-4xl">$1000</span>
      </p>
      <div class="flex flex-col gap-3">
        <h1 class="font-bold text-xl">This investment unlocks:</h1>
        <ul class="list-disc pl-3">
          <li>Lifetime access to the course content and materials.</li>
          <li>Regular course updates and new content.</li>
          <li>Exclusive access to a supportive online community.</li>
        </ul>
      </div>
      <div class="w-full">
        <button
          class="lg:px-10 px-6 rounded-xl py-3 lg:py-1o font-semibold bg-[#242099] text-white inline w-full"
        >
          Enroll Now
        </button>
      </div>
    </div>
  </section>
</template>