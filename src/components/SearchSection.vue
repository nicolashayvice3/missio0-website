<script setup>
import ImageGrid from "./ImageGrid.vue";
</script>

<template>
  <div class="relative flex w-full max-h-148">
    <img src="./images/logo-noname.jpg" class="flex relative object-cover" />
    <div
      class="absolute font-black texl-8xl text-black ml-24 mt-32 py-2 px-2 bg-origin-content rounded-md bg-orange-500"
    >
      <p>By Nicolas Hayvice-Caballe</p>
    </div>
  </div>
  <div class="flex text-black justify-items-center">
    <form action="" class="search-bar">
      <input type="search" name="search" pattern=".*\S.*" required />
      <button class="search-btn" type="submit">
        <span>Search</span>
      </button>
    </form>
  </div>
  <ImageGrid />
</template>
