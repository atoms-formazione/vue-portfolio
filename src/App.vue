<script setup lang="ts">
// import { RouterLink, RouterView } from "vue-router";
import TheNavBar from "./components/TheNavBar.vue";
import TheHero from "./components/TheHero.vue";
import AboutSection from "./components/AboutSection.vue";
import WorkSection from "./components/WorkSection.vue";
import ContactSection from "./components/ContactSection.vue";
</script>

<template>
  <header>
    <div>
      <the-nav-bar></the-nav-bar>
    </div>
    <div>
      <the-hero></the-hero>
    </div>
    <div>
      <about-section></about-section>
    </div>
    <div>
      <work-section></work-section>
    </div>
    <div>
      <contact-section></contact-section>
    </div>
  </header>
</template>

<style scoped></style>
