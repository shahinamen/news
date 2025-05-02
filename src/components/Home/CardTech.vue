<template>
  <div class="max-w-sm mx-auto">
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
      <img
        class="w-full h-48 object-cover"
        :src="Image"
        alt="Card
      Image"
      />
      <div class="p-1">
        <div class="flex pr-2"><Settings /> Board</div>
        <p class="text-gray-600 text-justify mt-2">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa
          reiciendis exercitationem ipsa odit hic itaque aliquid libero numquam,
          obcaecati ab nihil eos cum, perspiciatis atque eligendi possimus
          excepturi ducimus temporibus!
        </p>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";
import { Settings } from "lucide-vue-next";

const Image = ref(
  "https://images.pexels.com/photos/343457/pexels-photo-343457.jpeg"
);
</script>

<style scoped>
/* Add any additional styles here if needed */
</style>
