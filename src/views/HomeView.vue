<script lang="ts" setup>
import TheNavBar from "../components/TheNavBar.vue";
import TheHero from "@/components/TheHero.vue";
import AboutSection from "@/components/AboutSection.vue";
import WorkCase from "@/components/WorkCase.vue";
import TitleTextContact from "@/components/TitleTextContact.vue";
</script>
<template>
  <div class="home">
   <div>
    <TheNavBar />
   </div>
   <div>
    <TheHero />
   </div>
   <div>
   <AboutSection />
   </div>
   <div>
   <WorkCase />
  </div>
  <TitleTextContact />
</div>
</template>
