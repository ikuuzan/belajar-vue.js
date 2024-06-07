<script setup lang="js">
import { ButtonPrimary } from '@/components/buttons'
import { Testimoni } from '@/components'
import { Avatar1 } from '@/assets/img/index.js'


const testi = [
{
    desc: 'A must needed kit for every single software arhitect. It makes your coding life easier and your final product will be blooming.',
    name: 'Tiana Schleifer',
    job: 'CEO & Founder',
    image: Avatar1
},
{
    desc: 'A must needed kit for every single software arhitect. It makes your coding life easier and your final product will be blooming.',
    name: 'Tiana Schleifer',
    job: 'CEO & Founder',
    image: Avatar1
}
]
</script>



<template>
<section>


    <div class="flex flex-col mx-[25%] m-4">
        <h1 class="font-bold text-blue-950 m-auto text-3xl m-2">Customer Testimonials</h1>
        <p class="text-blue-900 m-auto text-wrap text-center">nim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
    </div>

<div class=" mt-[76px] grid grid-cols-2 gap-x-5">

    <!-- <article class=" bg-gray-200 p-8 flex flex-col mx-16 justify-center items-center text-wrap rounded-2xl">
        <h1 class="text-wrap text-blue-950 text-center mb-4 font-bold leading-8">
            "A must needed kit for every single software arhitect. It makes your coding life easier and your final product will be blooming."
        </h1>

        <div class="w-10 h-10 overflow-hidden rounded-full m-4">
            <img src="@/assets/img/avatar1.svg" alt="avatar">
        </div>
            <h1 class="font-bold ">Tiana Schleifer</h1>
            <p class="text-blue-600">CEO & Founder</p>
    </article> -->

<Testimoni 
    v-for="testimoni in testi"
    :desc="testimoni.desc"
    :name="testimoni.name"
    :job="testimoni.job"
    :image="testimoni.image"
    />


</div>
</section>

<section class="px-20  py-40  w-full">
    
<div class="flex justify-between">
    <div>
        <h1 class="font-bold text-4xl text-blue-950">Save time with Horizon.</h1>
        <h2 class="text-4   xl text-blue-950">Turn your visitors into clients.</h2>
    </div>
    <div class="flex">
        <ButtonPrimary text="Try Demo" type="outline"/>
        <ButtonPrimary text="Get Started Now" type="solid"/>
    </div>
</div>
</section>

</template>