<template>
  <div class="flex-container">
    <div class="titleText" id="about">
      <TitleText></TitleText>
    </div>
    <div class="case-studies">
      <CaseStudy1></CaseStudy1>
      <caseStudy2></caseStudy2>
    </div>
  </div>
</template>

<script setup lang="ts">
import CaseStudy1 from './caseStudy1.vue';
import caseStudy2 from './caseStudy2.vue';
import TitleText from './titleText.vue';
const sectionTitle = "work";

</script>

<style scoped>

</style>
