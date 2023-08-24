<script setup>




</script>

<template>
    <section id="project" class="project">
        <h2 class="project-highlights">Project Highlights</h2>
        <div class="grid">
            <div class="grid-item">
                <a href="https://afrin321.github.io/roadstar.ui/" target="_blank">
                    <div class="image bg3"></div>
                </a>
                <b style="margin-top: 20px;">Powershell Automate!</b>
                <p>GitHub Repo for scaffolding automation</p>
            </div>
            <div  class="grid-item">
                <a href="https://afrin321.github.io/roadstar.ui/" target="_blank">
                <div class="image bg2"></div>
            </a>
                <b style="margin-top: 20px;">RoadStar UI</b>
                <p>A UI interface booking vehicles.</p>
            </div>
            <div class="grid-item">
                <a href="https://afrin321.github.io/dolami-coding-test-afrin-haque/" target="_blank">
                    <div class="image bg3"></div>
                </a>
                <b style="margin-top: 20px;">AvaTown</b>
                <p>E-commerce UI with pagination + filter</p>
            </div>
        </div>
    </section>  
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Orelega+One&display=swap');
   
    a {
        text-decoration: none;
        color: inherit;
        cursor: pointer;
    }
    .project {
        box-sizing: border-box;
        flex-shrink: 0;
        width: 100%;
        height: min-content; /* 991px */
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        padding: 100px 100px 100px 100px;
        background-color: #fdfdff;
        overflow: hidden;
        position: relative;
        /* align-content: center; */
        flex-wrap: nowrap;
        gap: 60;
        border-radius: 0px 0px 0px 0px;
    }

    .project-highlights {
        flex-shrink: 0;
        /* width: 1px; */
        height: auto; /* 58px */
        /* white-space: pre-wrap;
        word-wrap: break-word;
        word-break: break-word; */
        max-width: 100% !important;
        overflow: visible;
        /* flex: 1 0 0px; */
        position: relative;
        font-weight: 400;
        font-style: normal;
        font-family: "Orelega One", sans-serif;
        color: #546a7b;
        font-size: 48px;
        letter-spacing: 0em;
        line-height: 1.2;
        text-align: left;
    }

    .grid {
        flex-shrink: 0;
        /* width: 1px; */
        height: min-content; /* 673px */
        min-height: auto;
        width: auto;
        display: grid;
        mix-blend-mode: luminosity;
        overflow: visible;
        /* flex: 1 0 0px; */
        position: relative;
        grid-template-columns: repeat(3, minmax(200px, 1fr));
        justify-content: center;
        grid-auto-rows: min-content;
        grid-template-rows: repeat(2, auto);
        grid-gap: 30px;
        padding: 0px 0px 0px 0px;
    }

    .grid-item {
        display: flex;
        flex-direction: column;     
        font-family: "Martian Mono", monospace;
        font-weight: 400;
        font-style: normal;
        justify-content: space-evenly;
    }

    

    @media only screen and (max-width: 1020px) {

        .project {
            padding: 80px;
        }

        .project-highlights {
            text-align: center;
        }
        .grid {            
            grid-template-columns: auto auto;
            justify-content: center;
            grid-auto-rows: min-content;
            grid-gap: 60px;
        }

        .image {
            flex-shrink: 0;
            width: 294px;
            height: 300px;
            display: block;
            -webkit-filter: grayscale(1);
            filter: grayscale(1);
            overflow: hidden;
            position: relative;
            justify-self: start;
            align-self: start;
            aspect-ratio: 0.98 / 1;
            
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            border-radius: 20px;
        }
    }

    @media only screen and (max-width: 810px) { 
        .grid {            
            grid-template-columns: auto;
            justify-content: center;
            grid-auto-rows: min-content;
        }
    }

    .image {
        flex-shrink: 0;
        width: 294px;
        /* height: 500px; */
        min-height: 200px;
        height: auto;
        display: block;
        -webkit-filter: grayscale(1);
        filter: grayscale(1);
        overflow: hidden;
        position: relative;
        justify-self: start;
        align-self: start;
        /* aspect-ratio: 0.98 / 1; */
        /* background-image: url(../assets/project1.png); */
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
        border-radius: 40px;
    }

    .bg1 {
        background-image: url(../assets/project1.png);
    }

    .bg2 {
        background-image: url(../assets/project4.png);
    }

    .bg3 {
        background-image: url(../assets/project3.png);
    }

    .bg4 {
        background-image: url(../assets/project4.png);
    }
    
</style>
