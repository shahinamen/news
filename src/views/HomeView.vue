<script setup lang="ts">
import { ref } from "vue";
import CardTech from "@/components/Home/CardTech.vue";
import ButtonGroup from "@/components/Home/ButtonGroup.vue";
import Card from "@/components/Home/Card.vue";
const Badminton = ref(
  "https://images.pexels.com/photos/209977/pexels-photo-209977.jpeg"
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
        <div class="col-span-2 bg-white p-4 rounded shadow">
          <img
            class="w-full object-cover"
            :src="Badminton"
            alt="Card
      Image"
          />
        </div>
        <div class="col-span-1 bg-white p-4 rounded shadow"><Card /></div>
        <div class="col-span-1 bg-white p-4 rounded shadow"><CardTech /></div>
      </div>
    </section>
  </main>
</template>
