<template>
  <header class="p-4 flex justify-between items-center">
    <h1
      class="text-2xl font-bold bg-white rounded-full shadow-md p-2 hover:shadow-lg transition duration-300 ease-in-out flex items-center"
    >
      <Grip class="cursor-pointer" />
    </h1>
    <div class="relative flex items-center w-full max-w-md pl-4 px-2">
      <Search class="absolute left-7 text-gray-500" />
      <input
        type="text"
        class="border rounded-full p-2 pl-12 shadow-md w-full focus:outline-none focus:ring-2 focus:ring-blue-500"
      />
    </div>
    <nav>
      <ul class="flex space-x-4">
        <li
          class="hover:bg-white hover:transition duration-300 ease-in-out p-2"
        >
          <Settings class="cursor-pointer" />
        </li>
      </ul>
    </nav>
  </header>
</template>
<script setup lang="ts">
import { Grip, Search, Settings } from "lucide-vue-next";
</script>
