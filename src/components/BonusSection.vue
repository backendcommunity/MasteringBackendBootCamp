<script>
export default {
  name: 'learnSection'
}
</script>


<template>
  <section
    class="mb-52 flex flex-col gap-5 w-5/6 container mx-auto items-center w-full justify-center"
  >
    <div class="w-full flex flex-col gap-6 items-center">
      <h2 class="font-bold text-2xl lg:text-6xl">Don't Miss These Bonuses At Checkout</h2>
      <p class="lg:text-xl text-center">
        Take Your Skills to the next level by claiming these special bonuses at checkout.
      </p>
    </div>

    <main class="flex gap-10 flex-col">
      <div class="flex flex-col md:flex-row items-center my-10 gap-10">
        <div class="flex flex-col lg:w-1/2 lg:py-20 gap-10 w-full justify-start items-start">
          <h1 class="font-bold text-xl lg:py-4 lg:text-5xl">
            Access MB Platform Premium Free for 6 Months
          </h1>
          <p class="lg:text-lg text-justify">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum nec ex sed mauris
            placerat ornare ac at leo. Nulla facilisi. Vivamus tempus varius aliquet. Donec et
            vestibulum sem, sit amet maximus ipsum.
          </p>
        </div>
        <div class="flex w-full border-4 lg:w-2/4 rounded-xl justify-end">
          <img alt="logo" class="w-full" src="../assets/techpad.gif" />
        </div>
      </div>

      <div class="flex flex-col md:flex-row items-center my-10 gap-10">
        <div class="flex w-full border-4 lg:w-2/4 rounded-xl">
          <img alt="logo" class="w-full" src="../assets/techpad.gif" />
        </div>
        <div class="flex flex-col lg:w-1/2 lg:py-20 gap-10 w-full justify-start items-start">
          <h1 class="font-bold text-xl lg:py-4 lg:text-5xl">Build Unlimited Premium Projects</h1>
          <p class="lg:text-lg text-justify">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum nec ex sed mauris
            placerat ornare ac at leo. Nulla facilisi. Vivamus tempus varius aliquet. Donec et
            vestibulum sem, sit amet maximus ipsum.
          </p>
        </div>
      </div>

      <div class="flex flex-col md:flex-row items-center my-10 gap-10">
        <div class="flex flex-col lg:w-1/2 lg:py-20 gap-10 w-full justify-start items-start">
          <h1 class="font-bold text-xl lg:py-4 lg:text-5xl">
            6 Months Free Access to BackendInterviewPrep
          </h1>
          <p class="lg:text-lg text-justify">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum nec ex sed mauris
            placerat ornare ac at leo. Nulla facilisi. Vivamus tempus varius aliquet. Donec et
            vestibulum sem, sit amet maximus ipsum.
          </p>
        </div>
        <div class="flex w-full border-4 lg:w-2/4 rounded-xl justify-end">
          <img alt="logo" class="w-full" src="../assets/techpad.gif" />
        </div>
      </div>
    </main>
  </section>
</template>