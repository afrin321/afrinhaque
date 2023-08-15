<script setup>




</script>

<template>
    <section id="background" class="background">
        <div class="">
            <div class="image"></div>
        </div>
        <div>
            <h2 class="background-title">Background</h2>
            <h3 class="right">Meet the software maestro with a knack for cybersecurity and 2 years of professional experience under their belt. Currently diving deep into the virtual world of network protection, our protagonist is sharpening their skills and building a diverse cyber repertory! </h3>
        </div>        
    </section>  
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Orelega+One&display=swap');
   
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

    .background > div {
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
        background-image: url(../assets/light.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
        border-radius: 100px;
    }

</style>
