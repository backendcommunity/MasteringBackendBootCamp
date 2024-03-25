<script>

export default {
    name: "CountDown"
}

</script>

<template>
    <section
        class="lg:mx-32 rounded-xl lg:p-16 p-2 flex flex-col items-center gap-10 lg:gap-20 border-2 border-[#303030] bg-white">
        <div class="flex flex-col lg:gap-16 gap-6 text-[#303030]">
            <h1 class="font-bold lg:text-5xl text-xl text-center"> Unlock Your Backend Development Potential in [X
                Days]!</h1>
            <p class="text-center lg:text-3xl  font-semibold">Don't wait! Enroll now and get instant access to
                the course
                materials to
                start learning in minutes.</p>
        </div>

        <div class=" grid grid-cols-4 gap-2 lg:gap-10 w-full">
            <div class="col-span-1 gap-4 flex flex-col items-center rounded-xl bg-[#8F03A1] text-white py-4 lg:py-6">
                <p class="font-bold lg:text-8xl">22</p>
                <p class="lg:lg:text-3xl text-xs">DAYS</p>
            </div>

            <div class="col-span-1 gap-4 flex flex-col items-center rounded-xl bg-[#8F03A1] text-white py-4 lg:py-6">
                <p class="font-bold lg:text-8xl">18</p>
                <p class="lg:text-3xl text-xs">HOURS</p>
            </div>
            <div class="col-span-1 gap-4 flex flex-col items-center rounded-xl bg-[#8F03A1] text-white py-4 lg:py-6">
                <p class="font-bold lg:text-8xl">40</p>
                <p class="lg:text-3xl text-xs">MINUTES</p>
            </div>
            <div class="col-span-1 gap-4 flex flex-col items-center rounded-xl bg-[#8F03A1] text-white py-4 lg:py-6">
                <p class="font-bold lg:text-8xl">02</p>
                <p class="lg:text-3xl text-xs">SECONDS</p>
            </div>

        </div>

        <div class="inline">
            <button
                class="lg:px-12 px-6 rounded-xl py-3  lg:py-6 font-semibold bg-[#242099] text-white inline text-2xl">
                Enroll Now
            </button>
        </div>
    </section>
</template>