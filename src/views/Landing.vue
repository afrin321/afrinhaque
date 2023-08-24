<script setup>
import Home from "./Home.vue"
import Background from "./Background.vue"
import Skills from "./Skills.vue"
import Projects from "./Projects.vue"
import Contact from "./Contact.vue"
import FooterSec from "./Footer.vue"
import Header from "../components/Header.vue"


</script>

<template>
    <div class="container">
        <Header />
        <main>
            <Home/>
            <Background />
            <Skills />
            <Projects />
            <Contact />
            <FooterSec />
        </main>
        
    </div>
    
  
</template>

<style scoped>
    .container {
        margin: 0px;
        padding: 0px;
        height: 100%;
        width: 100%;
    }

    main {
        position: relative;
        top: 0px;
    }
</style>
