<script setup lang="ts">
import Header from "@/components/Header.vue";
</script>

<template>
  <main>
    <section class="container mx-auto p-4">
      <h1 class="text-3xl font-bold mb-4">Welcome to My App</h1>
      <p class="text-gray-700">This is a simple Vue.js application.</p>
      <router-view />
    </section>
  </main>
</template>
