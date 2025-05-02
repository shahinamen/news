<script setup lang="ts">
import { ref } from "vue";
import CardTech from "@/components/Home/CardTech.vue";
import ButtonGroup from "@/components/Home/ButtonGroup.vue";
import Card from "@/components/Home/Card.vue";
import Footer from "@/components/Footer.vue";
const Badminton = ref(
  "https://images.pexels.com/photos/209977/pexels-photo-209977.jpeg"
);
const CardImage1 = ref(
  "https://images.pexels.com/photos/20555791/pexels-photo-20555791/free-photo-of-multiple-displays-mockup.jpeg"
);
const CardImage2 = ref(
  "https://images.pexels.com/photos/2115256/pexels-photo-2115256.jpeg"
);
const CardImage3 = ref(
  "https://images.pexels.com/photos/257872/pexels-photo-257872.jpeg"
);
</script>

<template>
  <main>
    <section
      class="container mx-auto p-1 bg-slate-100 rounded-lg shadow-md mt-4"
    >
      <div>
        <ButtonGroup />
      </div>
      <div class="grid grid-cols-4 gap-4 p-2">
        <div class="col-span-2 bg-white p-4 rounded shadow cursor-pointer">
          <img
            class="w-full object-cover rounded-lg"
            :src="Badminton"
            alt="Card
      Image"
            loading="lazy"
          />
        </div>
        <div class="col-span-1 bg-white p-4 rounded shadow">
          <Card class="cursor-pointer" />
        </div>
        <div class="col-span-1 bg-white p-4 rounded shadow">
          <CardTech class="cursor-pointer" />
        </div>
      </div>
      <div class="grid grid-cols-4 gap-4 p-2">
        <div class="bg-white p-4 rounded shadow cursor-pointer">
          <div class="relative group">
            <img
              class="w-full object-cover rounded-lg"
              :src="CardImage1"
              alt="Card Image"
              loading="lazy"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-50 flex flex-col justify-center items-center text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg"
            >
              <h2 class="text-lg font-semibold mt-2">Computer Desk</h2>
              <p class="text-gray-300">Desk description goes here.</p>
            </div>
          </div>
        </div>
        <div class="bg-white p-4 rounded shadow cursor-pointer">
          <figure>
            <video class="w-full rounded-lg" style="min-height: 185px" controls>
              <source
                src="https://videos.pexels.com/video-files/31851491/13568899_2560_1440_60fps.mp4"
                type="video/mp4"
              />
            </video>
          </figure>
        </div>
        <div class="bg-white p-4 rounded shadow cursor-pointer">
          <div class="relative group">
            <img
              class="w-full object-cover rounded-lg"
              :src="CardImage2"
              alt="Card Image"
              loading="lazy"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-50 flex flex-col justify-center items-center text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg"
            >
              <h2 class="text-lg font-semibold mt-2">Computer Mouse</h2>
              <p class="text-gray-300">Computer Mouse Description here</p>
            </div>
          </div>
        </div>
        <div class="bg-white p-4 rounded shadow cursor-pointer">
          <div class="relative group">
            <img
              class="w-full object-cover rounded-lg"
              :src="CardImage3"
              alt="Card Image"
              loading="lazy"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-50 flex flex-col justify-center items-center text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg"
            >
              <h2 class="text-lg font-semibold mt-2">Computer KeyBoard</h2>
              <p class="text-gray-300">Computer Keyboard Description.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Footer />
  </main>
</template>
