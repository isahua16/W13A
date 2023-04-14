<template>
    <footer>
        <h2>LOGO</h2>
        <div class="link-container">
            <a href="">Careers</a>
            <a href="">Contact</a>
            <a href="">Partners</a>
        </div>

        <div class="link-container">
            <a href="">Privacy Policy</a>
            <a href="">Return Policy</a>
        </div>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    footer {
        justify-self: center;
        width: 90%;
        min-height: 30vh;
        display:grid;
        place-items: center;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    }

    .link-container{
        display: grid;
        grid-auto-flow: row;
        row-gap: 10px;
    }

    a {
        text-decoration: none;
        color: black;
        font-size: 1.3rem;
        transition: transform 0.3s ease-in;
    }

    a:hover {
        transform: scale(1.1);
    }
</style>