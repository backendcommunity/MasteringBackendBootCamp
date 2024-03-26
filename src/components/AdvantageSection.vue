<script lang="ts">

export default {
    name: 'AdvantageSection'
}

</script>


<template>
    <section class="flex flex-col items-center  py-20 lg:px-16  gap-20 ">
        <div class="w-full lg:w-[600px] flex flex-col gap-6">
            <h1 class="font-bold text-2xl lg:text-4xl text-center">Our Advantage</h1>
            <p class="lg:text-xl text-center">BSed interdum auctor risus, sed fringilla purus lacinia ac. Quisque ut
                ipsum nec erat
                porttitor finibus eget vel turpis. Phasellus volutpat purus a enim</p>
        </div>

        <main class="flex lg:grid grid-cols-3 flex-col gap-10 items-center justify-center w-full
        ">
            <div class=" col-span-2 flex flex-col lg:grid grid-cols-2 gap-10 h-fit ">
                <div class="col-span-1  flex flex-col gap-8 p-5 border border-black rounded-2xl bg-white py-10">
                    <div class="flex flex-col gap-5">
                        <h1 class="font-semibold text-2xl">Other Courses</h1>
                        <ul class="list-disc flex flex-col gap-3 pl-5">
                            <li>Lifetime access to the course content and materials.</li>
                            <li>Regular course updates and new content.</li>
                            <li>Exclusive access to a supportive online community.</li>
                        </ul>
                    </div>
                    <b class="font font-extrabold text-4xl">
                        $3000
                    </b>
                </div>
                <div class="col-span-1   flex flex-col gap-8 p-5 border border-black rounded-2xl bg-white py-10">
                    <div class="flex flex-col gap-5">
                        <h1 class="font-semibold text-2xl">Other Courses</h1>
                        <ul class="list-disc flex flex-col gap-3 pl-5">
                            <li>Lifetime access to the course content and materials.</li>
                            <li>Regular course updates and new content.</li>
                            <li>Exclusive access to a supportive online community.</li>
                        </ul>
                    </div>
                    <b class="font font-extrabold text-4xl">
                        $3000
                    </b>
                </div>
            </div>



            <div
                class="col-span-1   flex flex-col gap-8 p-5 border border-black rounded-2xl text-white py-10  bg-gradient-to-tr to-[#322EB0] from-[#8F03A1]">
                <div class="flex flex-col gap-5">
                    <h1 class="font-semibold text-2xl">Other Courses</h1>
                    <ul class="list-disc flex flex-col gap-3 pl-5">
                        <li>Lifetime access to the course content and materials.</li>
                        <li>Regular course updates and new content.</li>
                        <li>Exclusive access to a supportive online community.</li>
                        <li>Regular course updates and new content.</li>
                        <li>Exclusive access to a supportive online community.</li>
                        <li>Regular course updates and new content.</li>

                    </ul>
                </div>
                <b class="font font-extrabold text-4xl">
                    $300
                </b>
            </div>
        </main>
    </section>
</template>