<script setup lang="js">

import ButtonPrimary from "@/components/buttons/ButtonPrimary.vue";
import { Phone } from "@/components/icons"

</script>

<template>
<!-- product  -->
<section id="product" class=" flex w-full pt-20 ">
  <div class="w-[50%] justify-center m-2">
    
    <!-- gambar & text  -->
      <div class="flex mx-16">
        <img class="w-6 h-6" src="@/assets/img/icon.svg"  alt="icon" >
        <h1 class="mx-2 text-blue-600 font-bold text-md">TRENDIEST TAILWIND TEMPLATE</h1>
      </div>

  
<!--full text -->
      <div class="flex flex-col mx-16">
        <h1 class="m-auto text-7xl justify-start ">Take your website to the next level with Horizon UI</h1>
        <h1 class="text-blue-600 text-xl my-4 text-wrap">Save hundreds of hours trying to create and develop a dashboard from scratch.
           The fastest, most responsive & trendiest dashboard is here. Seriously</h1>
      </div>

      <div class="flex my-4 mx-16">
        <ButtonPrimary text="Get Started Now!" type="solid"/>
        <ButtonPrimary text="Book a Free Call" type="phone"/>
      </div>
  </div>


  <!-- gambar -->
  <div class="w-[50%] flex justify-end">
    <img class="size-[80%]" src="@/assets/img/img.svg"  alt="gambar">
  </div>    
</section>  
    
</template>