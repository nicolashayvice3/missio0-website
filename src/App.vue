<script setup>
import HeaderPage from "./components/HeaderPage.vue";
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
      <div class="grid grid-flow-row">
        <SearchSection />
      </div>
    </main>
  </div>
</template>
