<template>
    <Head>
        <Title>SAVEEFFORTS.COM</Title>
    </Head>
    <div class="bg-[#000837] md:h-screen w-screen">
        <div class="flex items-center justify-center py-10">
            <img class="md:w-32 w-16" :src="logo" alt="">
            <h2 class="text-center text-2xl md:text-7xl font-bold text-white">SAVE<span
                    class="text-[#FFC03D]">EFFORTS</span>.COM</h2>
        </div>
        <div class="grid grid-cols-12 items-center px-5">
            <section class="col-span-4">
                <img :src="p1" alt="">
            </section>
            <section class="col-span-4">
                <div class="flex justify-center">
                    <img class="w-8/12" :src="arrow" alt="">
                </div>
                <h4 class="text-xl font-bold md:text-5xl text-center text-white">Al & Automation</h4>
            </section>
            <section class="col-span-4">
                <img :src="p2" alt="">
            </section>
        </div>
        <div class="mt-10">
            <h3 class="text-center text-white text-2xl md:text-4xl font-bold">Operate Business like Uber i.e. Automated &
                Scalable</h3>
        </div>
    </div>
</template>

<script setup>
import p1 from 'assets/images/left.png'
import p2 from 'assets/images/right.png'
import logo from 'assets/images/logo2.jpg'
import arrow from 'assets/images/arrow.png'


</script>