<script>
export default {
    name: "FaqSection",
    data() {
        return {
            showAnswer: {}, // Initialize showAnswer as an empty object
            faqs: [
                { id: 1, question: "What are the prerequisites for this course?", answer: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, nesciunt dignissimos repellendus iste autem ex dolorum blanditiis. Ipsum accusamus ullam omnis incidunt, tenetur ratione, eos eius sint aliquam id vitae?" },

                { id: 2, question: "What are the prerequisites for this course?", answer: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, nesciunt dignissimos repellendus iste autem ex dolorum blanditiis. Ipsum accusamus ullam omnis incidunt, tenetur ratione, eos eius sint aliquam id vitae?" },

                { id: 3, question: "What are the prerequisites for this course?", answer: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, nesciunt dignissimos repellendus iste autem ex dolorum blanditiis. Ipsum accusamus ullam omnis incidunt, tenetur ratione, eos eius sint aliquam id vitae?" },

                { id: 4, question: "What are the prerequisites for this course?", answer: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, nesciunt dignissimos repellendus iste autem ex dolorum blanditiis. Ipsum accusamus ullam omnis incidunt, tenetur ratione, eos eius sint aliquam id vitae?" },

                { id: 5, question: "What are the prerequisites for this course?", answer: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, nesciunt dignissimos repellendus iste autem ex dolorum blanditiis. Ipsum accusamus ullam omnis incidunt, tenetur ratione, eos eius sint aliquam id vitae?" },
                // Add more FAQs as needed
            ]
        };
    },
    methods: {
        toggleAnswer(id) {
            this.showAnswer[id] = !this.showAnswer[id]; // Toggle the visibility of the answer
        }
    }
};
</script>

<template>
    <section class="py-10 flex flex-col items-center gap-10 pb-32">
        <div class="w-full lg:w-[600px] flex flex-col gap-6 items-center">
            <h1 class="font-bold text-2xl lg:text-4xl">FAQ</h1>
            <p class="lg:text-xl text-center">Here are some commonly asked questions about the Backend Development
                Online Course</p>
        </div>
        <main class="flex flex-col gap-4 lg:w-[900px]">
            <div v-for="faq in faqs" :key="faq.id" class="flex flex-col gap-3 w-full">
                <button @click="toggleAnswer(faq.id)"
                    class="bg-white shadow-md border rounded-2xl lg:p-5 p-2 flex lg:px-10 justify-between w-full items-center">
                    <p class="lg:text-xl text-xs font-medium">{{ faq.question }}</p>
                    <svg xmlns="http://www.w3.org/2000/svg" class="lg:w-6 lg:h-6  w-4 h-4"
                        :class="{ 'transform rotate-180': showAnswer[faq.id] }" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M19 9l-7 7-7-7"></path>
                    </svg>
                </button>
                <p v-show="showAnswer[faq.id]" class="text-xs lg:text-base">{{ faq.answer }}</p>
            </div>
        </main>
    </section>
</template>
