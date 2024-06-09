<script setup lang="js">

import {  } from "@/components/buttons";
import ButtonPrimary from "./buttons/ButtonPrimary.vue";

</script>
<template>

    <!-- navbar -->
<nav class="bg-white p-4 fixed w-full mx-2  top-0" >
     
     <div class="  justify-between flex">
       <div href="#">
          <img alt="logo" class="mx-2" src="@/assets/img/logo.png" href="#" />
       </div>
   
       <ul class="flex justify-between px-8 ">
         <li><a href="#product" class="text-blue-950 px-8 font-bold">Product</a></li>
         <li><a href="#feature" class="text-blue-950 px-8 font-bold">Feature</a></li>
         <li><a href="#pricing" class="text-blue-950 px-8 font-bold">Pricing</a></li>
         <li><a href="#company" class="text-blue-950 px-8 font-bold">Company</a></li>
       </ul>
   
       <div class=" flex mx-2">
        <ButtonPrimary text="Login" type="outline"/>
        <ButtonPrimary text="Sign Up" type="solid"/>
       </div>
   
     </div>
   </nav>


</template>