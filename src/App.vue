<script setup>
import HeaderPage from "./components/HeaderPage.vue";
import ImageGrid from "./components/ImageGrid.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <HeaderPage />
    </div>
  </header>

  <main>
    <ImageGrid />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}
</style>
