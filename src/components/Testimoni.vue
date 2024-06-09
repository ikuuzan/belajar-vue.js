<script setup lang="js">
defineProps({
    desc: String,
    name: String,
    job: String,
    image: String
})

</script>

<template>

<article class=" bg-gray-200 p-8 flex flex-col mx-16 my-8 justify-center items-center text-wrap rounded-2xl">
        <h1 class="text-wrap text-blue-950 text-center mb-4 font-bold leading-8">
           {{ desc }}
        </h1>

        <div class="w-16 h-16 overflow-hidden rounded-full m-4">
            <img :src="image" alt="avatar">
        </div>
            <h1 class="font-bold ">{{ name }}</h1>
            <p class="text-blue-600">{{ job }}</p>
    </article>

</template>