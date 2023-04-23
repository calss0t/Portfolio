<template>
    <div>
        <h2>Portfolio</h2>
        <div id="Card">
            <NuxtLink to="https://play.google.com/store/apps/details?id=com.tomotabi.TomoTabi" target="_blank">
                <div class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row 
                hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                    <img class="object-cover rounded-t-lg md:rounded-none md:rounded-l-lg" src="./../images/TomoTabi.png"
                        alt="">
                    <div class="flex flex-col justify-between p-4 leading-normal">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">TomoTabi</h5>
                        <h6 class="mb-2 tracking-tight text-gray-900 dark:text-white">Fullstack developer and product owner
                        </h6>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Android application to plan your
                            next trip with your friends and keep track of expenses and how much money is owed after the
                            trip. This app is deployed on the Google Store play.</p>
                    </div>
                </div>
            </NuxtLink>
        </div>
        <div id="Card">
            <NuxtLink to="https://github.com/calss0t/Saga" target="_blank">
                <div class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row 
                hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                    <img class="object-cover rounded-t-lg md:rounded-none md:rounded-l-lg" src="./../images/Saga.png"
                        alt="">
                    <div class="flex flex-col justify-between p-4 leading-normal">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Saga</h5>
                        <h6 class="mb-2 tracking-tight text-gray-900 dark:text-white">Backend developer</h6>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Saga is an app that displays the top
                            movies and TV shows of the moment. It also let's you make reviews and activate/deactivate an
                            adult filter. As the backedn developer leader, I worked on acquiring an API key, created all the
                            routes and worked on creating the database.
                        </p>
                    </div>
                </div>
            </NuxtLink>
        </div>
        <div id="Card">
            <NuxtLink to="https://github.com/calss0t/Saga" target="_blank">
                <div class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row 
                hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                    <img class="object-cover rounded-t-lg md:rounded-none md:rounded-l-lg" src="./../images/Saga.png"
                        alt="">
                    <div class="flex flex-col justify-between p-4 leading-normal">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Twin shot</h5>
                        <h6 class="mb-2 tracking-tight text-gray-900 dark:text-white">Fullstack developer</h6>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Twin shot is Web application that helps
                            you keep up to date with your favourite sport teams and leagues.
                        </p>
                    </div>
                </div>
            </NuxtLink>
        </div>
        <div id="Card">
            <NuxtLink to="https://github.com/calss0t/Saga" target="_blank">
                <div class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row 
                hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                    <img class="object-cover rounded-t-lg md:rounded-none md:rounded-l-lg" src="./../images/Restore.png"
                        alt="">
                    <div class="flex flex-col justify-between p-4 leading-normal">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Restore</h5>
                        <h6 class="mb-2 tracking-tight text-gray-900 dark:text-white">Fullstack developer</h6>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Restore is a web application where you
                            can play games.
                        </p>
                    </div>
                </div>
            </NuxtLink>
        </div>
    </div>
</template>

<script setup>
// definePageMeta({
//     layout: 'portfolio'
// })
</script>

<style scoped>
#Card {
    margin: auto;
    width: 60%;
    justify-content: center;
    margin-bottom: 50px;
}

img {
    margin: 10px;
    width: 300px;
    height: 300px;
}

/* div {
    margin: auto;
} */

h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

p {
    margin: 20px;
}
</style>