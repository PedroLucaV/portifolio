<template>
    <div class="project">
        <img class="img-main" :src="img" alt="">
        <h1 class="title-project">{{ title }}</h1>
        <p class="project-para">{{ paragraph }}</p>
    </div>
</template>


<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    img: {
        type: String,
        required: true
    },
    paragraph: {
        type: String,
        required: true
    },
  },
};
</script>

<style scoped>
    .project{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        color: white;
        gap: 20px;
    }
    .img-main{
        width: 239px;
    }
    .title-project{
        font-size: 32px;
        text-align: center;
        width: 271px;
    }
    .project-para{
        width: 271px;
        text-align: center;
        font-size: 20px;
    }
</style>