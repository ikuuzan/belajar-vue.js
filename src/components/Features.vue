<script setup lang="js">



defineProps({
    logo: Object,
    title: String,
    desc: String, 
})

</script>

<template>
    <section>
<div class="container m-auto flex w-full ">
<div class="py-4">
    <div class="rounded-md">

      <div class="bg-blue-700 flex w-24 h-24 m-auto rounded-lg">
        <component :is="logo" class="w-16 h-16 m-auto"/>
      </div>

    <h1 class="font-bold text-2xl text-center my-2">{{ title }}</h1>
    <h2 class="text-wrap text-center ">{{ desc }}</h2>
    
    </div>
  </div>
</div>
</section>

</template>