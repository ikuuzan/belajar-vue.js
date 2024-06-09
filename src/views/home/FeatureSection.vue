<script setup lang="js">
import { Chart, Chevron, Mail, User } from '@/components/icons'
import { ButtonPrimary } from '@/components/buttons'
import { Features } from "@/components"

const feature = [
  {
  
  title: "Share team inboxes",
  desc: "Wheter you have a team of 2 or 200, our shared team inboxes keep everyone",
  logo: Mail,
  },
  {
  
  title: "Analytics Dashboard",
  desc: "Wheter you have a team of 2 or 200, our shared team inboxes keep everyone",
  logo: Chart,
  },
  {
  
  title: "Deliver Instructor",
  desc: "Wheter you have a team of 2 or 200, our shared team inboxes keep everyone",
  logo: User,
  }
]

</script>


<template>

<!-- Feature -->
<section id="feature" class="pt-28 container flex flex-col m-auto justify-center ">

<div>
  <h1 class="text-center justify-center text-4xl text-blue-950 ">How Horizon works?</h1>
  <p class="text-center justify-center p-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia inventore im</p>
</div>


<div class="flex justify-center items-center"> 


  <div class="flex items-center p-6 m-auto justify-center w-6 h-6 bg-blue-800 text-white text-xl font-bold rounded-full">1</div>
<div class="justify-center p-1 m-1 text-wrap">
  <h1 class="font-bold">Create your Account</h1>
  <h1 class="justify-center ">Lorem ipsum dolor sit amet consectetur
     adipisicing elit. Mollitia inventore im</h1>
</div>

<Chevron class="text-black  justify-center items-center w-40 h-40 m-auto"/> 

<div class="flex items-center p-6 m-auto justify-center w-6 h-6 border-2 text-black text-xl font-bold rounded-full">2</div>
<div class="justify-center items-center p-1 m-1 text-wrap">
  <h1 class="font-bold">Setup your account</h1>
  <h1 class="justify-center">Lorem ipsum dolor sit amet consectetur
     adipisicing elit. Mollitia inventore im</h1>
</div>

<Chevron class="text-black  justify-center items-center w-40 h-40 m-auto"/> 

<div class="flex items-center p-6 m-auto justify-center w-6 h-6 border-2 text-black text-xl font-bold rounded-full">3</div>
<div class="justify-center items-center p-1 m-1 text-wrap">
  <h1 class="font-bold">Start creating with Horizon</h1>
  <h1 class="justify-center">Lorem ipsum dolor sit amet consectetur
     adipisicing elit. Mollitia inventore im</h1>
</div>

</div>

</section>

<section class="py-40 container m-auto flex w-full ">

<!-- <div class="container m-auto flex w-full ">
 
  <div class="py-4">
    <div class="rounded-md">
      <div class="bg-blue-700 flex w-24 h-24 m-auto rounded-lg">
        <Mail class="w-16 h-16 m-auto"/>
      </div>
        <h1 class="font-bold text-2xl text-center my-2">Share team inboxes</h1>
      <h2 class="text-wrap text-center ">Wheter you have a team of 2 or 200, our shared team inboxes keep everyone</h2>
      </div>
  </div> -->
  
<Features
  v-for="fitur in feature"
  
  :title="fitur.title"
  :desc="fitur.desc"
  :logo="fitur.logo"
  />
<!-- 
  <div class="py-4 ">
    <div class="shadow-2xl shadow-gray-500 rounded-xl">
      <div class="bg-blue-700 flex w-24 h-24 m-auto rounded-lg">
        <Chart class="w-14 h-14 m-auto"/>
      </div>
      <h1 class="font-bold text-2xl text-center my-2">Anlytics dashboard</h1>
      <h2 class="text-wrap text-center ">Wheter you have a team of 2 or 200, our shared team inboxes keep everyone</h2>
    </div>
  </div>
  
  <div class="py-4">
    <div class="">
      <div class="bg-blue-700 flex w-24 h-24 m-auto rounded-lg">
        <User class="w-14 h-14 m-auto"/>
      </div>    
      <h1 class="font-bold text-2xl text-center my-2">Deliver Instructor</h1>
      <h2 class="text-wrap text-center ">Wheter you have a team of 2 or 200, our shared team inboxes keep everyone</h2>
    </div>
  </div>

</div> -->
</section>

</template>