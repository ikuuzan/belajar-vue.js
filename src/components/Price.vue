<script setup lang="js">

defineProps({

    harga: String,
    title: String,
    desc: String

})


</script>


<template>



       <div class="">
              <h1 class="text-5xl mx-2 text-blue-950 font-bold">{{ harga }}</h1>
              <p class="text-blue-950 mx-2 font-semibold">{{ title }}</p>
            <p class="text-blue-900 text-wrap mx-2">{{ desc }} </p>       
       </div>

</template>