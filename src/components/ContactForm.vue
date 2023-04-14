<template>
    <section>
        <h2>Contact Us</h2>
        <div>
            <input type="text" name="contact" placeholder="Your Name">
            <input type="text" name="contact" placeholder="Your Email">
            <input class="message-field" type="text" name="contact" placeholder="You Message">
            <button>Submit</button>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    section {
        width:100%;
        display: grid;
        place-items: center;
    }

    div {
        max-width: 900px;
        min-width: 250px;
        width: 100%;
        display:grid;
        row-gap: 12px;
    }

    input {
        border-radius: 10px;
        border: none;
        background-color: rgb(237, 237, 237);
        padding: 10px;
        font-size: 1.2rem;
    }

    button {
        font-size: 1.2rem;
        padding: 10px;
        border-radius: 10px;
        border: none;
    }
</style>