<script setup>
import Home from "./views/Home.vue"
import Background from "./views/Background.vue"
import Skills from "./views/Skills.vue"
import Projects from "./views/Projects.vue"
import Contact from "./views/Contact.vue"
import FooterSec from "./views/Footer.vue"

import { useRouter } from 'vue-router';

const router = useRouter();

</script>

<template>
    <router-view></router-view>
</template>

<style scoped>
    .container {
        margin: 0px;
        padding: 0px;
        height: 100%;
        width: 100%;
    }
</style>
