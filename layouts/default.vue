<template>
    <div>
        <div id="header_block">
            <header class="shadow-sm bg-white">
                <nav class="container mx-auto p-4 flex justify-between">
                    <NuxtLink to="/" class="font-bold">Pol Texido</NuxtLink> <!-- Change to logo -->
                    <ul class="flex gap-4">
                        <li>
                            <NuxtLink to="/"> <!-- no need for a path if same page -->
                                Home
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink :to="{ hash: '#about' }" :external="false"> <!-- no need for a path if same page -->
                                About
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink :to="{ hash: '#portfolio' }" :external="false">
                                <!-- no need for a path if same page -->
                                Portfolio
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink :to="{ hash: '#contact' }" :external="false"> <!-- no need for a path if same page -->
                                Contact me
                            </NuxtLink>
                        </li>
                    </ul>
                </nav>
            </header>
        </div>

        <div class="container">
            <slot />
        </div>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: green
}
nav {
    background-color: rgba(255, 255, 255, 0.373);
    /* flex-direction: row; */
    position: fixed;
    /* margin-bottom: 10px; */
}
</style>