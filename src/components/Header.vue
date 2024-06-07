<script setup lang="js">

import {  } from "@/components/buttons";
import ButtonPrimary from "./buttons/ButtonPrimary.vue";

</script>
<template>

    <!-- navbar -->
<nav class="bg-white p-4 fixed w-full mx-2  top-0" >
     
     <div class="  justify-between flex">
       <div class="">
          <img alt="logo" class="mx-2" src="@/assets/img/logo.svg" href="#" />
       </div>
   
       <ul class="flex justify-between px-8 ">
         <li><a href="#" class="text-blue-950 px-8 font-bold">Product</a></li>
         <li><a href="#feature" class="text-blue-950 px-8 font-bold">Feature</a></li>
         <li><a href="#pricing" class="text-blue-950 px-8 font-bold">Pricing</a></li>
       </ul>
   
       <div class=" flex mx-2">
        <ButtonPrimary text="Login" type="outline"/>
        <ButtonPrimary text="Sign Up" type="solid"/>
       </div>
   
     </div>
   </nav>


</template>