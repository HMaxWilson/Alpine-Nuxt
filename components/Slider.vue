<template>
  <Splide :options="{ rewind: true }">
    <SplideSlide>
      <div class="relative">
        <img class="max-h-[500px] w-full object-cover" src="/images/carousel/Stock1.jpg" alt="">
        <div class="absolute top-0 left-0 w-full h-full bg-black bg-opacity-50">
          <div class="flex flex-col justify-center h-full">
            <h1 class="text-lg md:text-3xl xl:text-5xl font-bold text-center text-white">The Local Maintenance Specialists You Can Trust</h1>
            <h2 class="text-base md:text-lg xl:text-2xl font-bold text-center text-white">Ensuring your holiday home is in safe hands</h2>
          </div>
        </div>
      </div>
    </SplideSlide>

    <SplideSlide>
      <div class="relative">
        <img class="max-h-[500px] w-full object-cover" src="/images/carousel/Stock2.jpg" alt="">
        <div class="absolute top-0 left-0 w-full h-full bg-black bg-opacity-50">
          <div class="flex flex-col justify-center h-full">
            <h1 class="text-lg md:text-3xl xl:text-5xl font-bold text-center text-white">Family Run Business</h1>
            <h2 class="text-base md:text-lg xl:text-2xl font-bold text-center text-white">Maintaining your family holiday home as if it was our own</h2>
          </div>
        </div>
      </div>
    </SplideSlide>

    <SplideSlide>
      <div class="relative">
        <img class="max-h-[500px] w-full object-cover" src="/images/carousel/Stock3.jpg" alt="">
        <div class="absolute top-0 left-0 w-full h-full bg-black bg-opacity-50">
          <div class="flex flex-col justify-center h-full">
            <h1 class="text-lg md:text-3xl xl:text-5xl font-bold text-center text-white">Knowing Your Unknown</h1>
            <h2 class="text-base md:text-lg xl:text-2xl font-bold text-center text-white">Experienced in knowing what you need before you know you need it!</h2>
          </div>
        </div>
      </div>
    </SplideSlide>
  </Splide>
</template>

<script setup>
import '@splidejs/splide/dist/css/splide.min.css';
import { Splide, SplideSlide } from '@splidejs/vue-splide'
</script>