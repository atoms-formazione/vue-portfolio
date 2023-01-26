<script setup lang="ts">
import TheNavBar from "./TheNavBar.vue";
import TheHero from "./TheHero.vue";
import AboutSection from "./AboutSection.vue";
</script>

<template>
  <div>
    <TheNavBar id="home"> </TheNavBar>
  </div>

  <div>
    <TheHero> </TheHero>
  </div>
  <div>
    <AboutSection id="about"></AboutSection>
  </div>
</template>

<style>
* {
  background-color: #fbf8cc;
}
/* template{
  height: 3984px;
  width: 1440px;
} */
</style>
