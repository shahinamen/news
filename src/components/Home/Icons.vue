<template>
  <div
    class="flex flex-row items-center justify-center bg-gradient-to-r from-red-200 to-yellow-200"
  >
    <Icon>
      <template #icon>
        <Facebook class="text-4xl text-blue-600" color="#FF0000" />
      </template>
      <template #label>
        <span class="text-sm mt-2">Facebook</span>
      </template>
    </Icon>
    <Icon>
      <template #icon>
        <Twitter class="text-4xl text-blue-600" color="#FF0000" />
      </template>
      <template #label>
        <span class="text-sm mt-2">Twitter</span>
      </template>
    </Icon>
    <Icon>
      <template #icon>
        <Instagram class="text-4xl text-blue-600" color="#FF0000" />
      </template>
      <template #label>
        <span class="text-sm mt-2">Instagram</span>
      </template>
    </Icon>
    <Icon>
      <template #icon>
        <Linkedin class="text-4xl text-blue-600" color="#FF0000" />
      </template>
      <template #label>
        <span class="text-sm mt-2">Linkedin</span>
      </template>
    </Icon>
    <Icon>
      <template #icon>
        <Youtube class="text-4xl text-blue-600" color="#FF0000" />
      </template>
      <template #label>
        <span class="text-sm mt-2">Youtube</span>
      </template>
    </Icon>
    <Icon>
      <template #icon>
        <Github class="text-4xl text-blue-600" color="#FF0000" />
      </template>
      <template #label>
        <span class="text-sm mt-2">Github</span>
      </template>
    </Icon>
  </div>
</template>

<script setup lang="ts">
import {
  Facebook,
  Twitter,
  Instagram,
  Linkedin,
  Youtube,
  Github,
} from "lucide-vue-next";
import Icon from "@/components/Home/Icon.vue";
</script>
