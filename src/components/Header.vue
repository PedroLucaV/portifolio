<script setup>
</script>

<template>
    <div class="header-cont">
        <div class="logo"><img src="/logo-blank.webp" alt=""></div>
        <ul class="list-header">
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contacts">Contact</a></li>
        </ul>
    </div>
</template>

<style scoped>
    .header-cont{
        position: fixed;
        align-self: start;
        width: 100vw;
        height: 140px;
        background-color: #FFC260;
        display: flex;
        justify-content: center;
        flex-direction: row;
        gap: 669px;
        align-items: center;
    }
    .list-header{
        list-style: none;
        display: flex;
        flex-direction: row;
        gap: 74px;
    }
    .list-header > li > a{
        text-decoration: none;
        color: black;
        font-size: 32px;
        font-weight: bold;
    }
    .logo > img{
        width: 100px;
        height: 100px;
    }
</style>