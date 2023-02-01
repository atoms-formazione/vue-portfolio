<script setup lang="ts">
import TitleText1 from "./TitleText1.vue";
import JobList from "./JobList.vue";
</script>

<template>
  <div>
    <TitleText1 id="titleText1Order"></TitleText1>
    <JobList id="jobListOrder"></JobList>
  </div>
</template>

<style scoped>
#titleText1Order {
  position: relative;
  top: 150px;
  left: 35px;
  padding-right: 470px;
}

#jobListOrder {
  position: relative;
  top: 175px;
  left: 160px;
  padding-right: 250px;
}
</style>
