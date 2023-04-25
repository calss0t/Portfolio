<template>
    <div id="block">
        <h2>Ability</h2>
        <p id="subtitle">My Skills</p>
        <div class="flex felx-row">
            <div id="skills_languages">
                <h5>Languages</h5>
                <h6>TypeScript, JavaScript, Python, CSS</h6>
                <h5>Frontend</h5>
                <h6>React, React Native, HTML, Django, Vue, Nuxt</h6>
                <h5>Backend</h5>
                <h6>PostgreSQL, Knex, Express, JWT</h6>
                <h5>Others</h5>
                <h6>Git, GitHub Projects, Postman, Mocha, Chai</h6>
            </div>
            <div id="languages">
                <h5>I speak in:</h5>
                <h6>English - Business Level (TOEIC 990)</h6>
                <h6>Spanish - Native</h6>
                <h6>Catalan - Native</h6>
                <h6>Japanese - Conversational (~N3)</h6>
                <h6>French - Basic</h6>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
/* #block{
    margin: auto;
    align-items: center;
} */

h2 {
    padding-top: 110px;
    color: #FF9849;
    font-family: 'Poppins-Medium';
    font-size: 24px;
    line-height: 36px;
    letter-spacing: 0.135em;
    text-transform: uppercase;
    text-align: center;
}

#subtitle {
    color: #071E48;
    font-family: 'Poppins-Bold';
    font-size: 48px;
    line-height: 72px;
    text-align: center;
    margin-bottom: 80px;
}

#skills_languages {
    margin-left: 172px;
    margin-right: 150px;
    padding-bottom: 114px;
}

h5 {
    font-family: 'Poppins-Bold';
    font-size: 32px;
    line-height: 48px;
    letter-spacing: 0.02em;
    color: #071E48;
    margin-bottom: 5px;
}

h6 {
    font-family: 'Poppins-SemiBold';
    font-size: 24px;
    line-height: 36px;
    letter-spacing: 0.02em;
    color: #071E48;
    margin-bottom: 20px;
}
</style>