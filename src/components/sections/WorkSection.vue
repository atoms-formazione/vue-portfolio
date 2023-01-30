<script setup lang="ts">
import TitleText from "../molecules/TitleText.vue";

const titleText = {
  title: "work.",
  text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
};
</script>

<template>
  <div class="about-container">
    <TitleText class="title-section" v-bind="titleText" />
  </div>
</template>

<style scoped>
.about-container {
  margin-top: 200px;
}

.title-section {
  margin-bottom: 145px;
}
</style>
