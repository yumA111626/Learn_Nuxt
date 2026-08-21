<template>
    <div class="container mx-auto max-w-2xl">
        <header class="flex justify-between">
            <div>
                <NuxtLink to = "/" class="text-xl font-semibold p-2 hover:bg-gray-200  ">Yuma Hanai</NuxtLink>
            </div>
            <nav>
                <ul class="flex space-x-4">
                    <li>
                        <NuxtLink to = "/">Main</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to  = "/about">About</NuxtLink>
                    </li>   
                </ul>
            </nav>
        </header> 
        <main class="p-2">
            <slot />
        </main> 
    </div>
</template>