<template>
    <main>
        <img src="/image.jpeg" alt="Image">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit soluta rerum totam, nulla velit pariatur itaque possimus animi quos inventore vel accusamus magni nam perferendis enim facere, dignissimos repellendus sequi!</p>
        <contact-form></contact-form>
    </main>
</template>

<script>
import ContactForm from '@/components/ContactForm.vue';
    export default {
        components: {
            ContactForm
        }
    }
</script>

<style scoped>
    main {
        justify-self: center;
        min-height: 60vh;
        width:90%;
        display: grid;
        place-items: center;
    }

    img {
        width: 100%;
        max-width: 900px;
    }

    p {
        width: 100%;
        max-width: 600px;
    }

</style>