<script setup lang="js">
import { Phone } from "@/components/icons"
defineProps({
    text: String,
    type: {
        default: "solid"
    }
})
</script>

<template>

<button v-if="type == 'solid'" class="py-2 text-white bg-blue-500 hover:bg-blue-700 rounded-xl mx-2 px-4">
    {{ text }}
</button>

<button v-else-if="type == 'outline'" class="py-2 font-semibold bg-white border-2 text-blue-500 hover:bg-blue-500 hover:text-white rounded-xl mx-2 px-4">
    {{ text }}
</button>

<button v-else-if="type == 'phone'" class="py-2 font-semibold bg-white border-2 text-blue-500 hover:bg-blue-500 hover:text-white rounded-xl mx-2 px-4">
    <Phone class="inline w-6 h-6 mr-3"/>
    {{ text }}
</button>
<button v-else-if="type == 'bulat'" class="w-6 h-6 p-4 items-center  font-bold bg-white border-2 text-blue-800 hover:bg-blue-800 hover:text-white rounded-full  ">
    
    {{ text }}
</button>



</template>