<script lang="ts">
import FirstSection from './FirstSection.vue'
export default {
    components: { FirstSection },
    name: "HeroSection"
}
</script>

<template>
    <section class=" grid grid-cols-2 gap-16 pt-10">
        <div class="col-span-1  flex flex-col justify-between">
            <div class="flex flex-col gap-8">
                <h1 class="text-5xl font-bold">Neque porro quisquam
                    est qui dolorem ipsum6
                </h1>
                <p class="text-2xl">Our comprehensive backend development course
                    will equip you with the skills to take your coding
                    career to the next level.
                </p>
            </div>
            <div class="inline">
                <button class="px-10 rounded-xl py-6 font-semibold bg-[#242099] text-white inline">
                    Enroll Now
                </button>
            </div>
        </div>
        <div class="col-span-1 flex flex-col justify-end items-end">
            <img alt="se" class="w-[600px]" src="../assets/vid.svg" />
        </div>

    </section>
</template>