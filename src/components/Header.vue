<script setup>
import src from '@/assets/logo_vue_300px.png'
</script>

<template>
    <header>
        <img :src alt="vue logo">
        <h1>Hi, I'm <span class="highlight">Vue</span></h1>
    </header>
</template>

<style scoped>
img {
    height: 150px;
}

h1 {
    font-size: 2rem;
    color: #34495e;
    margin-top: 10px;
}
</style>
