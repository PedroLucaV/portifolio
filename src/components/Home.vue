<script setup>
</script>

<template>
    <div id="home" class="container">
        <div class="photo">
            <img src="/logo-blank.webp" alt="">
        </div>
        <div class="hero-text">
            <h1 class="main-text-header">About Me</h1>
            <p class="hero-paragr">Sou Pedro Lucas Vasconcelos da Silva, um desenvolvedor back-end apaixonado por tecnologia desde jovem. Tenho especialização em Node.js, com foco em criar soluções seguras e eficientes. Ao longo da minha carreira, sempre busquei aprender e me aprimorar, estando em constante evolução. Minha motivação é usar a tecnologia para resolver problemas e facilitar a vida das pessoas. Estou sempre pronto para enfrentar novos desafios e contribuir com projetos inovadores, trazendo dedicação e curiosidade a cada nova oportunidade.</p>
        </div>
    </div>
</template>

<style scoped>
    .container{
        margin: auto;
        gap: 40px;
        display: flex;
        align-items: center;
        width: 70%;
        height: 1040px;
    }

    .hero-text{
        display: flex;
        flex-direction: column;
        gap: 15px;
    }
    .main-text-header{
        font-size: 32px;
    }
    .hero-paragr{
        font-size: 24px;
    }
    .photo > img{
        width: 338px;
        height: 338px;
    }
</style>