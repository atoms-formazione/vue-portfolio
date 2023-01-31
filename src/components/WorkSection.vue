<script setup lang="ts">
import TitleText2 from "./TitleText2.vue";
import CaseStudy1 from "./CaseStudy1.vue";
import CaseStudy2 from "./CaseStudy2.vue";
</script>

<template>
  <div>
    <TitleText2></TitleText2>
    <div class="cases">
      <CaseStudy1></CaseStudy1>
      <CaseStudy2></CaseStudy2>
    </div>
  </div>
</template>

<style scoped>
.cases {
  display: flex;
  gap: 10%;
  margin-left: 50px;
}
</style>
