<script lang="ts">

export default {
    name: 'CertificateSection'
}

</script>


<template>
    <section
        class="lg:p-20 lg:m-16 lg:my-40 p-5 flex flex-col lg:flex-row gap-10 items-center bg-gradient-to-r to-[#322EB0] from-[#8F03A1]  rounded-3xl">

        <div class="flex flex-col gap-6">
            <h1 class="lg:text-5xl text-xl  font-bold text-gray-200">Backend Engineering Certificate</h1>
            <p class=" text-gray-300 lg:text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum nec
                ex
                sed
                mauris placerat ornare ac
                at leo. </p>
        </div>
        <div class="bg-white rounded-2xl p-5">
            <img alt="logo" class=" lg:w-[700px] w-52" src="../assets/block.png" />
        </div>
    </section>
</template>