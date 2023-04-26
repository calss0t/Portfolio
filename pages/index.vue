<template>
    <div>
        <div id="top_block">
            <div class="flex flex-row">
                <img src="./../images/Profile-picture-2.jpg.png">
                <div>
                    <h3>Hello I'm</h3>
                    <h1>Pol Texido</h1>
                    <h2>Fullstack developer</h2>
                    <p>I'm a Full-Stack Software Engineer and I'm passionate about creating web applications and learning
                        new ways
                        to make those application look good. </p>
                    <div class="flex flex-row">
                        <a id="CV" href="./../images/Pol_Texido_Resume.pdf" target="_blank">Download My CV</a>
                        <!-- //Change this it dowload my CV -->
                        <NuxtLink :to="{ hash: '#contact' }" :external="false" id="contactMe">Contact Me</NuxtLink>
                    </div>
                </div>
            </div>


        </div>
        <About id="about" />
        <Skills id="skills" />
        <Portfolio id="portfolio" />
        <Contact id="contact" />

    </div>
</template>

<script setup>
function DowloadCV() {
    location.href = 'http://www.google.com'
}


</script>

<style scoped>
#top_block {
    margin: auto;
    align-items: center;
    align-content: center;
    width: 75%;
}

#about {
    width: 100%;
    background-color: #f5f5f5;
    /* margin-bottom: 190px; */
}

div {
    background-color: #F2F0ED;
}

h1 {
    font-family: 'Poppins-ExtraBold';
    font-size: 64px;
    line-height: 96px;
    letter-spacing: 0.015em;
    color: #FF9849;
    text-align: left;
}

h2 {
    font-family: 'Poppins-Regular';
    font-size: 36px;
    line-height: 54px;
    letter-spacing: -0.015em;
    color: #071E48;
    text-align: left;

}

h3 {
    padding-top: 221px;
    font-family: 'Poppins-ExtraBold';
    font-size: 36px;
    line-height: 54px;
    letter-spacing: 0.05em;
    color: rgba(123, 123, 123, 0.24);
    text-align: left;

}



p {
    font-family: 'Poppins-Medium';
    font-size: 16px;
    line-height: 24px;
    color: #7B7B7B;
    width: 55%;
}

#CV {
    background-color: #FF9849;
    border-radius: 31px;
    color: #FFFFFF;
    padding: 15px 20px;
    cursor: pointer;
    margin-top: 25px;
    margin-bottom: 160px;
    font-family: 'Mulish-Bold';
    font-size: 16px;
    line-height: 24px;
    display: flex;
    align-items: center;
    text-align: center;
    margin-right: 70px;
}

#contactMe {
    border: 2px solid #FF9849;
    border-radius: 31px;
    padding: 15px 20px;
    cursor: pointer;
    margin-top: 25px;
    margin-bottom: 160px;
    font-family: 'Mulish-Bold';
    font-size: 16px;
    line-height: 24px;
    display: flex;
    align-items: center;
    text-align: center;
    color: #FF9849;
}

img {
    padding-top: 138px;
    width: 60%;
    height: 800px;
    margin: auto;
}

/* #CV-text{
    font-family: 'Mulish-Bold';
    font-size: 16px;
    line-height: 24px;

    display: flex;
    align-items: center;
    text-align: center;

    color: #FFFFFF;
} */
</style>