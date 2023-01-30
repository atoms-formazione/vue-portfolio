<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import TheNavBar from "./components/TheNavBar.vue";
import TheHero from "./components/TheHero.vue";
</script>

<template>
  <header>
    <div>
      <the-nav-bar></the-nav-bar>
    </div>
    <div>
      <the-hero></the-hero>
    </div>
  </header>
</template>

<style scoped></style>
