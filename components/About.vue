<template>
    <div>
        <h2>About</h2>
        <p>I'm a full-stack developer that enjoys learning new things and meeting new people. I also love watching sports
            (every sport, even snooker and darts) and I love talking and discussing it with people. I also enjoy
            contributing to other people projects and working on my own ideas.</p>
        <div>
            <NuxtLink to="./../resume.pdf"  type="application/pdf" target="_blank">Resume</NuxtLink>

            <a href="./../resume.pdf" type="application/pdf" target="_blank">Resume 2</a>


        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 36px;
    text-align: center;
}

p {
    margin: 20px;
}
</style>