<script setup lang="ts">
import TheNavbar from "@/components/TheNavbar.vue";
import TheHero from "@/components/TheHero.vue";
import AboutSection from "@/components/AboutSection.vue";
import WorkSection from "@/components/WorkSection.vue";
import ContactSection from "@/components/ContactSection.vue";

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
    <AboutSection></AboutSection>
    <WorkSection></WorkSection>
    <ContactSection></ContactSection>
  </main>
</template>

<style scoped>
main {
  margin: 0 10px;
  /*margin: 104px 10px 0;*/
}

/*.nav-bar {
  width: 100%;
  top: 0;
  left: 0;
  position: fixed;
}*/
</style>
