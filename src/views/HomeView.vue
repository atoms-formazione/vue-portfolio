<script lang="ts" setup>
import TheNavBar from "../components/TheNavBar.vue";
import TitleText from "@/components/TitleText.vue";
import TheHero from "@/components/TheHero.vue";
import JobList from "@/components/JobList.vue";
</script>
<template>
  <div class="home">
   <div>
    <TheNavBar />
   </div>
   <div>
    <TheHero />
   </div>
   <TitleText />
  </div>
  <div> 
   <JobList />
  </div>
</template>
