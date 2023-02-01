<script setup lang="ts">
import TitleText2 from "./TitleText2.vue";
import CaseList from "./CaseList.vue";
</script>

<template>
  <div>
    <TitleText2 id="TitleText2Order"></TitleText2>
    <CaseList id="CaseListOrder"></CaseList>
  </div>
</template>

<style scoped>
#TitleText2Order {
  position: relative;
  bottom: -800px;
  left: -94px;
}
#CaseListOrder {
  position: relative;
  bottom: -310px;
  left: 100px;
  width: 44%;
}
</style>
