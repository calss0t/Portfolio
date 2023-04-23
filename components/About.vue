<template>
    <div id="block">
        <h2>About me</h2>
        <div id="about" class="flex flex-row">
            <img src="./../images/Profile-picture.jpg">
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
    margin: auto;
    border-bottom: 1px;
    border-style: solid;
    margin-top: 50px;
    margin-bottom: 50px;
    width: 85%;
    padding-bottom: 100px;
}

#about {
    margin: auto;
    width: 75%;
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

p {
    text-align: justify;
    align-self: center;
    margin: 20px;
}</style>