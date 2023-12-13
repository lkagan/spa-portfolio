<script setup>
defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <div>
        <section class="bg-gray-800 pt-16 h-screen px-72">
            <div class="h-2/3 flex flex-wrap content-between pb-36">
                <p class="border-b-2 font-bold border-gray-400 pb-3 text-gray-300 text-2xl uppercase">
                    Hey! This is Larry. I'm a Senior Software Engineer and I would
                    be glad to work with you
                </p>
            </div>
        </section>
        <section class="bg-gray-200 text-gray-800 px-72 py-10 h-screen">
            <h2 class="text-6xl font-bold pt-3">Skills</h2>
        </section>
        <section class="bg-gray-600 text-gray-200 px-72 py-10 h-screen">
            <h2 class="text-6xl font-bold pt-3">Projects</h2>
        </section>
        <section class="flex justify-between py-10 px-72 bg-gray-800 text-gray-300 text-xl">
            <p>&copy; larry.dev All rights ereserved.</p>
        <div class="flex justify-evenly items-center">
            GitHub
            Twitter
            StackOverflow
        </div>
        </section>
    </div>
</template>

<style>
.bg-dots-darker {
    background-image: url("data:image/svg+xml,%3Csvg width='30' height='30' viewBox='0 0 30 30' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1.22676 0C1.91374 0 2.45351 0.539773 2.45351 1.22676C2.45351 1.91374 1.91374 2.45351 1.22676 2.45351C0.539773 2.45351 0 1.91374 0 1.22676C0 0.539773 0.539773 0 1.22676 0Z' fill='rgba(0,0,0,0.07)'/%3E%3C/svg%3E");
}
@media (prefers-color-scheme: dark) {
    .dark\:bg-dots-lighter {
        background-image: url("data:image/svg+xml,%3Csvg width='30' height='30' viewBox='0 0 30 30' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1.22676 0C1.91374 0 2.45351 0.539773 2.45351 1.22676C2.45351 1.91374 1.91374 2.45351 1.22676 2.45351C0.539773 2.45351 0 1.91374 0 1.22676C0 0.539773 0.539773 0 1.22676 0Z' fill='rgba(255,255,255,0.07)'/%3E%3C/svg%3E");
    }
}
</style>
