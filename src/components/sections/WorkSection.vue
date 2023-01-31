<script setup lang="ts">
import TitleText from "../molecules/TitleText.vue";
import WorkCard from "../molecules/WorkCard.vue";

const titleText = {
  title: "work.",
  text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
};

const workCards = [
  {
    image: "card1",
    date: "November 24, 2019",
    title: "Some case study",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a convallis. Eget ipsum, velit vitae eu nunc, consequat, at.",
  },
  {
    image: "card2",
    date: "December 12, 2020",
    title: "Other case study",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a convallis. Eget ipsum, velit vitae eu nunc, consequat, at.",
  },
];
</script>

<template>
  <div class="work-container">
    <TitleText class="title-section" v-bind="titleText" />

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
