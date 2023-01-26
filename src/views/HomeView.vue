<script setup lang="ts">
import TheNavbar from "@/components/TheNavbar.vue";
import TheHero from "@/components/TheHero.vue";

const p1 = {
  firstName: "John",
  lastName: "Doe",
  residency: "Nederland",
  employment: "Product Designer",
  imgPath: "src/assets/BigAvatar.svg",
};
</script>

<template>
  <main>
    <TheNavbar class="nav-bar" v-bind="p1"></TheNavbar>
    <TheHero class="the-hero" v-bind="p1"></TheHero>
  </main>
</template>

<style scoped></style>
