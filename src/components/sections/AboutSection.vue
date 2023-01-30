<script setup lang="ts">
import AboutList from "../molecules/AboutList.vue";
import TitleText from "../molecules/TitleText.vue";

const titleText = {
  title: "about.",
  text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
};

const list = [
  {
    duration: "2014 - 2018",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
  {
    duration: "2018 - 2020",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
  {
    duration: "2020 - Present",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
];
</script>

<template>
  <div class="about-container">
    <TitleText class="title-section" v-bind="titleText" />
    <AboutList class="about-section" :list="list" />
  </div>
</template>

<style scoped>
.about-container {
  margin-top: 200px;
}

.title-section {
  margin-bottom: 145px;
}

.about-section {
  margin-left: 300px;
}
</style>
