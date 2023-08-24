<script setup>
import myFile from './../assets/AfrinHaque_CV.pdf';


const downloadFile = () => {
    const link = document.createElement('a');
      link.href = myFile;
      link.download = 'AfrinHaque_CV.pdf'; // Specify the desired filename for the downloaded file
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
}

</script>

<template>
    <section id="contact" class="contact">
        <h2 class="get-in-touch">Let's Discuss Your Project</h2>
        <div class="divisions">
            <form class="form" action="https://api.web3forms.com/submit" method="POST">
                <input type="hidden" name="access_key" value="fb785873-c1e6-4263-81da-67b01794ba87">
                <input class="input" type="text" name="name" placeholder="Subject/Title - Tell Us Your Digital Dreams 🌈" title="" />
                <input class="input" type="email" name="email" placeholder="cto@google.com - Drop Your Email 📧" title="cto@google.com - Drop Your Email 📧" />
                
                <input class="input" name="message" placeholder="Write Your Message - Greetings from Earth! 🌍" title="Write Your Message - Greetings from Earth! 🌍" value="Hi!"/>
                <!-- <div class="h-captcha" data-captcha="true"></div> -->
                <button class="send-btn" title="Way to go! (pun intended)">{{`Click to Transmit..`}}</button>
            </form>
            <div class="cv">                 
                <!-- <button class="cv-btn">Get My CV <span>⚙️</span></button> -->
                <!-- <p>📎 <span>Social Handles</span></p>
                <span class="links">
                    <a>🔗 <i>LinkedIn</i></a>
                    <a>🔗 <i>GitHub</i></a>
                    <a>🔗 <i>Medium</i></a>
                    <a>🔗 <i>Insta</i></a>
                </span>
                <hr/> -->
                <p>🌺 <span>Résumé</span></p>
                <span class="links">
                <a @click="downloadFile">🔗 <i @click="downloadFile">Web_Dev_CV</i></a>
                <a @click="downloadFile">🔗 <i @click="downloadFile">Cyber_Security_CV</i></a>
                </span>
            </div>
        </div>
    </section>  
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Orelega+One&display=swap');
   

   .contact {
        box-sizing: border-box;
        width: 100%;
        height: min-content; /* 800px */
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        padding: 100px 100px 100px 100px;
        background-color: #62929e;
        min-height: 100vh;
        overflow: hidden;
        position: relative;
        align-content: flex-start;
        flex-wrap: nowrap;
        border-radius: 0px 0px 0px 0px;
   }

   .get-in-touch {
        flex-shrink: 0;
        width: 100%;
        height: auto; /* 58px */
        white-space: pre-wrap;
        word-wrap: break-word;
        word-break: break-word;
        /* max-width: 1000px; */
        overflow: visible;
        position: relative;
        font-weight: 400;
        font-style: normal;
        font-family: "Orelega One", sans-serif;
        color: #393d3f;
        font-size: 48px;
        letter-spacing: 0em;
        line-height: 1.2;
        text-align: left;
   }

   .divisions {
        display: flex;
        width: 100%;


   }

   .form {
        display: flex;
        flex-direction: column;
        flex-basis: 50%;
        width: 100%;
        align-items: center;
   }

   .input {
        width: 100%;
        height: 50px;
        border: none;
        outline: none;
        border-radius: 100px;
        margin: 10px auto;
        text-indent: 1em;
        padding: 8px 12px;
        font-weight: 400;
        font-style: normal;
        font-family: "Martian Mono", monospace;
        color: #000000;
        font-size: 16px;
   }

   .send-btn {
        font-weight: 400;
        font-style: normal;
        font-family:  "Martian Mono", monospace;
        background-color: #393d3f;
        text-align: center;
        font-size: 16px;
        outline: none;
        border: none;
        border-radius: 40px 0px 40px 0px;
        width: 60%;
        min-height: 50px;
        padding: 12px 22px;
        color: azure;
        margin: 20px 50px;
   }

   .cv {
        display: flex;
        justify-content: flex-start;
        align-items: left;
        padding-left: 20%;
        flex-basis: 50%;
        height: auto;
        flex-direction: column;
        font-weight: 400;
        font-style: normal;
        font-family: "Martian Mono", monospace;
        color: azure;
       
        /* border: solid 2px red; */
   }

   .cv > p {
    font-size: 22px;

    
   }

 

   .cv > p > span {
    text-decoration: underline;
    text-decoration-color: lavenderblush;
    text-decoration-thickness: 4;
   }

   .cv > span > a {
    padding-right: 5px;
    padding-bottom: 3px;
   }
   .cv > span > a:hover, a:active {
    /* text-decoration: underline;
    text-decoration-color: #393d3f;
    text-decoration-thickness: 5px;
    text-decoration-skip: 2; */
    background: #393d3f;
    /* border-bottom: 3px solid #393d3f; */
    color: white;
    width: fit-content;
    
    
    
   }

   .links {
    width: 100%;
    /* border: solid 2px red; */
    display: flex;
    justify-content: space-evenly;
   }
   
   

   .cv > a:hover, a:active > i {
    /* text-decoration: underline;
    text-decoration-color: lavenderblush;
    text-decoration-thickness: 2; */
   }

   .cv-btn {
        height: auto;
        width: auto;
        outline: none;
        border: none;
        padding: 20px 22px 20px 22px;
        font-weight: 400;
        font-style: normal;
        font-family: "Martian Mono", monospace;
        background: #393d3f;
        color: #62929e;
        font-size: 20px;
        border-radius: 10px;
        /* background: transparent; */
       
   }

   @media only screen and (max-width: 810px) {
    .contact {
        padding: 40px;
        justify-content: center;
        align-items: center;
    }

    .divisions {
        flex-direction: column;
    }

    .send-btn {
        width: 90%;
    }

    .input::placeholder {
      white-space: normal;
      line-height: 1.2;
    }

    .cv {
        padding-top: 20px;
        padding-left: 5%;
    }

    .links {
        width: 100%;
        /* border: solid 2px red; */
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
    }

    
   }

   
   



   
</style>
