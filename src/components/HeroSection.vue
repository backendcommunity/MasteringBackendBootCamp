<script lang="ts">

export default {

    name: "HeroSection"
}
</script>

<template>
    <section class=" flex flex-col md:grid grid-cols-2 gap-16 md:pt-10 pt-5">
        <div class="col-span-1  flex flex-col gap-4 lg:justify-between">
            <div class="flex flex-col gap-4 lg:gap-8">
                <h1 class="lg:text-5xl text-2xl font-bold">Neque porro quisquam
                    est qui dolorem ipsum6
                </h1>
                <p class=" lg:text-2xl">Our comprehensive backend development course
                    will equip you with the skills to take your coding
                    career to the next level.
                </p>
            </div>
            <div class="inline">
                <button class="lg:px-10 px-6 rounded-xl py-3 lg:py-6 font-semibold bg-[#242099] text-white inline">
                    Enroll Now
                </button>
            </div>
        </div>
        <div class="col-span-1 flex flex-col justify-end items-end">
            <img alt="se" class="w-[600px]" src="../assets/vid.svg" />
        </div>

    </section>
</template>