<script lang="ts" setup>

const route = useRoute();
</script>

<template>
    <div class="min-h-screen w-full">
        <nav
            class="flex flex-row justify-center items-center gap-4 py-4 h-[10vh] sticky top-0 z-50 backdrop-blur bg-white/70 shadow-md">
            <NuxtLink href="/">
                <img class="h-12" src="~/assets/images/logo-16x9.png" alt="Logo">
            </NuxtLink>
            <NuxtLink href="/" :class="['un text-lg font-semibold', {
                'text-[var(--primary)]': route.path == '/'
            }]">
                Home
            </NuxtLink>
            <NuxtLink href="/schedule" :class="['un text-lg font-semibold', {
                'text-[var(--primary)]': route.path == '/schedule'
            }]">
                Schedule
            </NuxtLink>
            <NuxtLink href="/news" :class="['un text-lg font-semibold', {
                'text-[var(--primary)]': route.path == '/news'
            }]">
                News
            </NuxtLink>
            <NuxtLink href="/competitive-event-guidelines" :class="['un text-lg font-semibold', {
                'text-[var(--primary)]': route.path == '/competitive-event-guidelines'
            }]">
                Event Guidelines
            </NuxtLink>
        </nav>
        <main>
            <slot />
        </main>
    </div>
</template>

<style scoped>
.un {
    display: inline-block;
    background-image: linear-gradient(var(--primary) 0 0);
    background-position: 0 100%;
    /*OR bottom left*/
    background-size: 0% 2px;
    background-repeat: no-repeat;
    padding-bottom: 2px;
    transition:
        background-size 0.3s,
        background-position 0s 0.3s;
}

.un:hover {
    background-position: 100% 100%;
    /*OR bottom right*/
    background-size: 100% 2px;
    color: var(--primary);
}
</style>