<script setup>
import ProjectModel from './ProjectModel.vue';
</script>

<template>
    <div id="projects" class="project-container">
        <span class="header-projects">
            <h1>Projects</h1>
        </span>
        <div class="projects">
            <a href="https://github.com/PedroLucaV/agenda-maker/tree/back-end" target="blank">
                <ProjectModel title="Agenda Maker" paragraph="Projeto escolar de agendamento de horarios, fiquei responsavel pela criação da API na branch de Back-End com o ExpressJS e MySQL com a ORM Sequelize" img="/agenda_maker.png"/>
            </a>

            <ProjectModel title="Project 02" paragraph="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tempus ligula vel ante gravida consequat. Donec volutpat vel." img="/logo-blank.webp"/>

            <ProjectModel title="Project 03" paragraph="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tempus ligula vel ante gravida consequat. Donec volutpat vel." img="/logo-blank.webp"/>

        </div>
    </div>
</template>

<style scoped>
    a{
        text-decoration: none;
    }
    .project-container{
        background-color: #FF4E45;
        display: flex;
        flex-direction: column;
        align-items: center;
        height: 683px;
    }
    .header-projects>h1{
        font-size: 58px;
        color: white;
        margin-top: 57px;
    }
    .projects{
        margin-top: 55px;
        display: flex;
        gap: 177px;
    }
</style>