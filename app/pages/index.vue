<template>
    <div class="index h-[calc(100vh-8.3rem)] flex flex-col justify-center items-center border dark:border-gray-500">
        <h1 class="mt-2">Installed items: </h1>
        <p class="mt-2">
            <strong>Nuxt 3</strong>, 
            <strong>Pinia</strong>,
            <strong>Tailwind CSS</strong>, 
            <strong>VueUse</strong>, 
            <strong>NuxtImage</strong>,
            <strong>shadcn-vue</strong>,
            <strong>@radix-icons/vue</strong>
        </p>
        

        <ClientOnly>
     
        </ClientOnly>

    </div>
</template>

<script setup>

</script>

<style lang="postcss" scoped>
.active{
    @apply bg-black text-white rounded-full dark:bg-white dark:text-black;
}
</style>