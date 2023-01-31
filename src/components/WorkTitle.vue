<template>
  <div class="titleWork">
    <h1>{{ title }}</h1>
    <p>{{ textTitle }}</p>
  </div>
</template>
<script setup lang="ts">
import { ref } from "vue";
const title = ref("work.");
const textTitle = ref(
  "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam."
);
</script>
<style>
.titleWork h1 {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 800;
  font-size: 100px;
  color: #f7f197;
  padding: 0px 30px;
}
.titleWork p {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  color: #03045e;
  padding-left: 30px;
  padding-right: 100px;
}
</style>
