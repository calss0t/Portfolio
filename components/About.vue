<template>
    <div id="block">
        <h2>Intro</h2>
        <p id="subtitle">About me</p>
        <div id="text">
            <p>I'm a full-stack developer that enjoys learning new things and meeting new people. I love watching
                sports
                (every sport, even snooker and darts) and I love talking and discussing it with people. I also enjoy
                contributing to other people projects and working on my own ideas.</p>
        </div>

    </div>
</template>

<script setup>

</script>

<style scoped>
#block {
    background-color: #f5f5f5;
    margin: auto;
    border-bottom: 1px;
    border-style: solid;
    margin-top: 50px;
    width: 85%;
}

#subtitle {
    color: #071E48;
    font-family: 'Poppins-Bold';
    font-size: 48px;
    line-height: 72px;
    text-align: center;
}

h2 {
    padding-top: 193px;
    color: #FF9849;
    font-family: 'Poppins-Medium';
    font-size: 24px;
    line-height: 36px;

    letter-spacing: 0.135em;
    text-transform: uppercase;

    text-align: center;
}


img {
    width: 300px;
    height: 300px;
}

h2 {
    margin-bottom: 20px;
    font-size: 36px;
    text-align: center;
}

#text {
    width: 35%;
    margin: auto;
    text-align: center;
    padding-bottom: 190px;
}

p {
    font-family: 'Poppins-Regular';
    font-size: 20px;
    line-height: 156%;
    color: #7B7B7B;
    text-align: center;
    align-self: center;
}
</style>