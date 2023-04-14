<template>
    <header>
        <h1>LOGO</h1>
        <nav>
            <a href="">About</a>
            <a href="">Cart</a>
        </nav>
    </header>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    header {
        justify-self: center;
        width: 90%;
        min-height: 10vh;
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        place-items: center;    
    }

    nav {
        display: grid;
        grid-auto-flow: column;
        align-items: center;
        column-gap: 20px;
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