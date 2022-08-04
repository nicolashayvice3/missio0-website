<script setup>
import HeaderPage from "./components/HeaderPage.vue";
import ImageGrid from "./components/ImageGrid.vue";
import SearchSection from "./components/SearchSection.vue";
</script>

<template>
  <div>
    <header>
      <div>
        <HeaderPage />
      </div>
    </header>

    <main>
      <SearchSection />
      <ImageGrid />
    </main>
  </div>
</template>
