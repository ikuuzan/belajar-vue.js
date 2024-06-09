<script setup lang="js">

import { Price } from "@/components"


const price = [
  {
  
  harga: "340+",
  title: "Successful Project",
  desc: "Lorem ipsum dolor sit, amet consectetur adipisicing elit."
  },
  {
  
  harga: "2,8K",
  title: "Client Worldwide",
  desc: "Lorem ipsum dolor sit, amet consectetur adipisicing elit."
  },
  {
  
  harga: "$10m",
  title: "Annual Percentage Rate",
  desc: "Lorem ipsum dolor sit, amet consectetur adipisicing elit."
  },
  {
  
  harga: "7000+",
  title: "Daily Visits",
  desc: "Lorem ipsum dolor sit, amet consectetur adipisicing elit."
  }
  
]

</script>


<template>

<section id="pricing" class="flex">
    <div class="flex container mt-16 m-auto">
        <div class="m-auto m-32 mx-28 flex flex-col">
                <h1 class="text-3xl text-blue-950 font-bold mx-4">Boost your workflow with Horizon</h1>
                <p class="text-blue-900 text-wrap mb-4 mx-4 mr-8">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error est delectus, atque sequi nisi rerum ipsam magnam, labore molestiae porro, facere cum molestias.</p>
                <div class="flex grid grid-rows-2 grid-flow-col gap-4">
                
                <!-- <div class="flex grid grid-rows-2 grid-flow-col gap-4">
                        <div class="">
                            <h1 class="text-5xl mx-2 text-blue-950 font-bold">340+</h1>
                            <p class="text-blue-950 mx-2 font-semibold">Successful Project</p>
                            <p class="text-blue-900 text-wrap mx-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>       
                        </div>
                        <div>
                            <h1 class="text-5xl mx-2 text-blue-950 font-bold">2,8k</h1>
                            <p class="text-blue-950 mx-2 font-semibold">Client Worldwide</p>
                            <p class="text-blue-900 text-wrap mx-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>       
                        </div>
                        <div>
                            <h1 class="text-5xl mx-2 text-blue-950 font-bold">$10m</h1>
                            <p class="text-blue-950 mx-2 font-semibold">Annual Percentage Rate</p>
                            <p class="text-blue-900 text-wrap mx-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>       
                        </div>
                        <div>
                            <h1 class="text-5xl mx-2 text-blue-950 font-bold">7000+</h1>
                            <p class="text-blue-950 mx-2 font-semibold">Daily Visit</p>
                            <p class="text-blue-900 text-wrap mx-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>       
                        </div>
                    </div> -->

                    <Price v-for="jual in price"

                    :harga="jual.harga"
                    :title="jual.title"
                    :desc="jual.desc"
                    />

</div>
        </div>
        <img class="w-[30%] h-[30%] m-auto my-20" src="@/assets/img/thunder.svg" alt="thunder">
    </div>
</section>


</template>