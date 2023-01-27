<template>
  <div class="flex-container">
    <div class="titleText" id="about">
      <TitleText></TitleText>
    </div>
    <div class="case-studies">
      <CaseStudy1></CaseStudy1>
      <CaseStudy2></CaseStudy2>
    </div>
  </div>
</template>

<script setup lang="ts">
import CaseStudy1 from './caseStudy1.vue';
import CaseStudy2 from './caseStudy2.vue';
import TitleText from './titleText.vue';
const sectionTitle = "work";

</script>

<style scoped>
.case-studies{
  display: flex;
  justify-content: space-around;
  margin-top: 5rem;
  flex-wrap: wrap;
}

.flex-container{
  margin-top: 5rem;
}
</style>
