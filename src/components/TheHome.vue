<script setup lang="ts">
import TheNavBar from "./TheNavBar.vue";
import TheHero from "./TheHero.vue";
import AboutSection from "./AboutSection.vue";
import WorkSection from "./WorkSection.vue";
import TheContact from "./TheContact.vue";
</script>

<template>
  <TheNavBar id="home"> </TheNavBar>
  <TheHero> </TheHero>
  <AboutSection></AboutSection>
  <WorkSection></WorkSection>
  <TheContact></TheContact>
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
