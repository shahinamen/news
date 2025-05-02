<template>
  <div
    class="flex flex-col items-center justify-center m-4 cursor-pointer hover:transition duration-300 ease-in-out"
  >
    <div class="p-2 bg-white shadow-md rounded-full">
      <slot name="icon" />
    </div>
    <slot name="label" />
  </div>
</template>
