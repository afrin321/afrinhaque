<script setup>




</script>

<template>
    <section id="background" class="background">
        <div class="div-2">
            <div class="image" title="Hi, this is me!"></div>
            <h3 class="right">I truly believe in the transformative power of reading, learning, applying, and sharing knowledge!</h3>
        </div>
        <div>
            <h2 class="background-title">Background</h2>
            <h3 class="right">Hi! I'm Afrin, a passionate web developer exploring the diverse areas of tech. I find modern technology fascinating, how it transforms years of striving into an automated process within days. </h3>
            <h3 class="right">Often, you will find me diving deep into an emerging tech field. Currently, I am dedicatedly studying cyber security, understanding how security works in the industry.</h3>
            <h3 class="right">At this moment, I offer web development services including front-end development, api development and full-stack application building.</h3>
            <h3 class="right">As the landscape of modern technologies grows increasingly intricate, I'm committed to investing time and effort into mastering emerging domains such as AI, data science, Blockchain, cloud computing, and DevOps.</h3>
            
        </div>        
    </section>  
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Orelega+One&display=swap');
   
    .div-2 {
        display: flex; 
        flex-direction: column;
        padding-right: 10%;
        
    }
    .background {
        
        box-sizing: border-box;
        flex-shrink: 0;
        width: 100%;
        height: min-content; /* 548px */
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        align-items: flex-start;
        padding: 100px 100px 100px 100px;
        background-color: #393d3f;
        overflow: visible;
        position: relative;
        align-content: center;
        flex-wrap: nowrap;
        gap: 0;
        border-radius: 0px 0px 0px 0px;
    }

    @media only screen and (max-width: 810px) {
        .background {
            flex-direction: column;
        }
    }

    @media only screen and (max-width: 640px) {
        .background {
            flex-direction: column;
            padding: 50px;
        }
    }


    .background-title {
        flex-shrink: 0;
        width: 1px;
        height: auto; /* 58px */
        /* white-space: pre-wrap;
        word-wrap: break-word;
        word-break: break-word; */
        overflow: visible;
        flex: 1 0 0px;
        position: relative;
        font-weight: 400;
        font-style: normal;
        font-family: "Orelega One", sans-serif;
        color: #c6c5b9;
        font-size: 48px;
        letter-spacing: 0em;
        line-height: 1.2;
        text-align: left;
    }

    .right {
        flex-shrink: 0;
        width: 100%;
        height: auto; /* 270px */
        white-space: pre-wrap;
        word-wrap: break-word;
        word-break: break-word;
        overflow: visible;
        position: relative;
        font-weight: 400;
        font-style: normal;
        font-family: "Martian Mono", monospace;
        color: #ffffff;
        font-size: 20px;
        letter-spacing: 0em;
        line-height: 1.5;
        text-align: left;
    }

    .background > div:first {
        flex-basis: 50%;
    }
    .background > div:first-of-type {
        display: flex;
        justify-content: flex-start;
        align-items: flex-start;
        padding-top: 50px;
    }

    .image {
        flex-shrink: 0;
        width: 80px;
        height: 80px;
        display: block;
        -webkit-filter: grayscale(1);
        filter: grayscale(1);
        overflow: hidden;
        position: relative;
        aspect-ratio: 1 / 1;
        background-image: url(../assets/1666490187156.JPEG);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
        border-radius: 100px;
    }

</style>
