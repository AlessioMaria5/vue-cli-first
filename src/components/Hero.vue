<template>
    <div class="hero">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Large_Scaled_Forest_Lizard.jpg" alt="">
    </div>
  </template>

<script>
export default {

    name: 'myHero'
}
</script>

<style>

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
    .hero {

        width: 100%;
        height: 300px;
    }
    img {
        width: 100%;
        height: 100%;
        overflow: hidden;
        object-fit: cover; /* per immagine sopra */
        
        /* width: 100%;
        height: 150%;
        object-fit: cover;
        overflow: hidden;  CON TITOLO AL CENTRO */
    }
</style>