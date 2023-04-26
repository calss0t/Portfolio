<template>
    <div>
        <div id="block">
            <h2>Pol Texido</h2>
            <h3>pol.texido.b@gmail.com</h3>
            <div id="contact_links">
                <NuxtLink to="https://www.linkedin.com/in/pol-texido/" target="_blank"><img id="linkedIn" src="./../images/LinkedIn-icon.png"></NuxtLink>
                <NuxtLink to="https://github.com/calss0t" target="_blank"><img id="github" src="./../images/Github-icon.png"></NuxtLink>
                <NuxtLink to="mailto:pol.texido.b@gmail.com" target="_blank"><img id="email" src="./../images/email.png"></NuxtLink>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
#block {
    background-color: #FF9D52;
    padding-bottom: 137px;
}

h2 {
    padding-top: 125px;
    font-family: 'Poppins-ExtraBold';
    font-size: 64px;
    line-height: 96px;
    letter-spacing: 0.015em;
    color: #FBE3B2;
    text-align: center;
}

h3 {
    font-family: 'Poppins-SemiBold';
    font-size: 32px;
    line-height: 48px;
    color: #FFFFFF;
    text-align: center;
    padding-bottom: 15px;
}

#contact_links {
    margin-top: 15px;
    background-color: rgba(251, 227, 178, 0.38);
    border-radius: 54px;
    margin: auto;
    width: 15%;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-top: 10px;
    padding-bottom: 10px;
}

img{
    height: 40px;
    width: 40px;
    margin-left: 30px;
}
img:hover{
    opacity: 0.2;
}
</style>