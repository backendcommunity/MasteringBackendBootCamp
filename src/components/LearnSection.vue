<script>
export default {
  name: 'learnSection'
}
</script>


<template>
  <section
    class="mb-52 py-10 flex flex-col gap-20 w-5/6 container mx-auto items-center w-full justify-center"
  >
    <div class="w-full flex flex-col gap-6 items-center">
      <h1 class="font-bold text-2xl lg:text-6xl">
        The Ultimate Solution to Master Backend Engineering Step-by-Step
      </h1>
      <p class="lg:text-xl text-center">
        Backend developers are the backbone of the tech industry. By completing this course, you'll
        be equipped to:
      </p>
    </div>

    <main class="flex gap-10 flex-col">
      <div class="flex flex-col md:flex-row items-center my-10 gap-10">
        <div
          class="flex flex-col lg:w-1/2 lg:py-20 gap-10 lg:w-3/4 w-full justify-start items-start"
        >
          <h1 class="font-bold text-xl lg:py-4 lg:text-5xl">Build a Content Automation App</h1>
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
        <div
          class="flex flex-col lg:w-1/2 lg:py-20 gap-10 lg:w-3/4 w-full justify-start items-start"
        >
          <h1 class="font-bold text-xl lg:py-4 lg:text-5xl">Build a Social Media Management App</h1>
          <p class="lg:text-lg text-justify">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum nec ex sed mauris
            placerat ornare ac at leo. Nulla facilisi. Vivamus tempus varius aliquet. Donec et
            vestibulum sem, sit amet maximus ipsum.
          </p>
        </div>
      </div>

      <div class="flex flex-col md:flex-row items-center my-10 gap-10">
        <div
          class="flex flex-col lg:w-1/2 lg:py-20 gap-10 lg:w-3/4 w-full justify-start items-start"
        >
          <h1 class="font-bold text-xl lg:py-4 lg:text-5xl">Code 4 Mini Projects</h1>
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

      <div class="md:flex grid grid-cols-1 flex-col lg:flex-row items-center my-10 gap-10">
        <div class="flex flex-col gap-5 w-full lg:w-2/3">
          <div class="flex justify-center gap-5 w-full">
            <div class="px-5 w-1/2 py-8 text-center border-2 border-gray-300">
              Great Backend Engineer
            </div>
          </div>
          <div class="flex gap-5 w-full">
            <div class="px-5 w-full text-center py-8 border-2 border-gray-300">Node.js</div>
            <div class="px-5 w-full text-center py-8 border-2 border-gray-300">PHP</div>
          </div>

          <div class="md:flex gap-5 w-full grid grid-cols-2">
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Express</div>
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Laravel</div>
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Nuxt.js</div>
          </div>
          <div class="md:flex gap-5 grid grid-cols-2 w-full">
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Postgres</div>
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Docker</div>
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Redis</div>
            <div class="px-5 w-full py-8 text-center border-2 border-gray-300">Kafka</div>
          </div>
          <div class="md:flex gap-5 w-full grid grid-cols-2">
            <div class="px-3 w-full py-8 text-center border-2 border-gray-300">Team work</div>
            <div class="px-3 w-full py-8 text-center border-2 border-gray-300">Trust</div>
            <div class="px-3 w-full py-8 text-center border-2 border-gray-300">Collaboration</div>
            <div class="px-3 w-full py-8 text-center border-2 border-gray-300">Projects</div>
            <div class="px-3 w-full py-8 text-sm text-center border-2 border-gray-300">
              <p class="w-full">Communication</p>
            </div>
            <div class="px-5 w-full md:hidden block py-8 text-center border-2 border-gray-300">
              Land Your Dream Backend Job
            </div>
          </div>
          <div class="md:flex justify-center hidden md:block gap-5 w-full">
            <div class="px-5 w-1/2 py-8 text-center border-2 border-gray-300">
              Land Your Dream Backend Job
            </div>
          </div>
        </div>
        <div class="flex flex-col lg:w-1/2 lg:py-10 gap-10 w-full justify-start items-start">
          <h1 class="font-bold text-xl lg:text-4xl">
            In-Demand Backend Programming Languages and Technologies
          </h1>
          <p class="lg:text-lg text-justify">
            JavaScript, Node.js, PHP, Express, Laravel, Nuxt.js, Postgres, Docker, Redis, Kafka
          </p>
        </div>
      </div>
    </main>
  </section>
</template>