<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Header from "@/components/Header.vue";
import Icons from "@/components/Home/Icons.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <div
    class="bg-gradient-to-r from-red-200 to-yellow-200 min-h-screen flex flex-col"
  >
    <Header />
    <Icons />
    <RouterView />
  </div>
</template>

<style scoped></style>
