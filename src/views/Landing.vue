<script setup>
import Home from "./Home.vue"
import Background from "./Background.vue"
import Skills from "./Skills.vue"
import Projects from "./Projects.vue"
import Contact from "./Contact.vue"
import FooterSec from "./Footer.vue"


</script>

<template>
    <div class="container">
        <Home/>
        <Background />
        <Skills />
        <Projects />
        <Contact />
        <FooterSec />
    </div>
    
  
</template>

<style scoped>
    .container {
        margin: 0px;
        padding: 0px;
        height: 100%;
        width: 100%;
    }
</style>
