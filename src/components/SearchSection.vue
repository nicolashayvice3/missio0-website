<script setup>
import ImageGrid from "./ImageGrid.vue";
</script>

<template>
  <div class="relative flex w-full max-h-148">
    <img src="./images/logo-noname.jpg" class="flex object-cover text-center" />
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
