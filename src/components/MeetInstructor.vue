<script lang="ts">

export default {
    name: "MeetInstructor"
}

</script>

<template>
    <section class="lg:p-20 flex flex-col items-center justify-center w-full  gap-10">
        <h1 class="lg:text-4xl font-bold text-2xl ">Meet your Instructor </h1>
        <main
            class="lg:mx-20 lg:p-20 p-5 bg-white rounded-2xl  border-2 border-gray-400 flex flex-col gap-10 items-center b">
            <div class=" flex flex-col justify-center items-center gap-1">
                <img alt="logo" class=" w-20 lg:w-46" src=" ../assets/client image.svg" />
                <p class="lg:text-3xl font-bold text-xl">Solomon Eseme</p>
                <p class="lg:text-xl">Founder, MasteringBackend</p>
            </div>

            <div class="text-center lg:text-xl lg:px-20 ">Your guide on this journey is [Instructor Name], a seasoned
                backend
                developer with
                over [X Years] of
                experience building enterprise-grade applications. [He/She] has a passion for empowering others and is
                dedicated to making you a backend pro.
            </div>

            <div class=" w-full items-center flex justify-center">
                <button class="lg:px-10 px-6 rounded-xl py-3 lg:py-6 font-semibold bg-[#242099] text-white ">
                    Learn More About the Instructor Button
                </button>
            </div>

        </main>
    </section>
</template>