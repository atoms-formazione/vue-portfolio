<script setup lang="ts">
import WorkCard from './WorkCard.vue';
import TitleTextWork from './TitleTextWork.vue';
const workCards = [
  {
    image: "Caso",
    date: "November 24, 2019",
    title: "Some case study",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a convallis. Eget ipsum, velit vitae eu nunc, consequat, at.",
  },
  {
    image: "caso02",
    date: "December 12, 2020",
    title: "Other case study",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a convallis. Eget ipsum, velit vitae eu nunc, consequat, at.",
  },
];
</script>

<template>
  <div class="work-container">
    <TitleTextWork />

    <div class="cards-wrapper">
      <WorkCard v-for="card in workCards" :key="card.date" v-bind="card" />
    </div>
  </div>
</template>

<style scoped>
.work-container {
  margin-top: 200px;
}
.title-section {
  margin-bottom: 145px;
}
.cards-wrapper {
  display: flex;
  gap: 120px;
}
</style>