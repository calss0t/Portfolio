<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4">
                <NuxtLink to="/" class="font-bold"> Nuxt Dojo</NuxtLink>
            </nav>
        </header>

        <div class="container mx-auto p-4">
            <slot />
        </div>

        <footer class="container mx-auto p-4 felx justify-between border-t-2">
            <ul class="felx gap-4">
                    <li>
                        <NuxtLink to="/"> Home </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about"> About </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/portfolio"> Portfolio </NuxtLink>
                    </li>
                </ul>
        </footer>
    </div>
</template>

<style scoped>
    /* body {
        background-color: coral;
    } */
    h2 {
        font-size: 60px;
    }
    .router-link-exact-active {
        color: green
    }
</style>