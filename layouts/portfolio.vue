<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/"> Nuxt Dojo</NuxtLink>
                
            </nav>
        </header>

        <div>
            <slot />
        </div>

        <footer>
            <ul>
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
    .router-link-exact-active {
        color: green
    }
</style>