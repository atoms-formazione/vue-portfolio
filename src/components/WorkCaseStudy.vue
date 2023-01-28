<script setup lang="ts">
let caseStudyList = [
  {
    img: "src/assets/CaseStudy1.svg",
    date: "November 24, 2019",
    title: "Some Case Study",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. " +
      "Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
  {
    img: "src/assets/CaseStudy2.svg",
    date: "November 24, 2019",
    title: "Some Case Study",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. " +
      "Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
];
</script>
<template>
  <div class="container">
    <div class="card" v-for="(cs, index) in caseStudyList" :key="index">
      <img class="cs-img" :src="cs.img" :alt="'case-study-' + (index + 1)" />
      <p class="cs-date">{{ cs.date }}</p>
      <h3 class="cs-title">{{ cs.title }}</h3>
      <p class="cs-description scrollbar-style">{{ cs.description }}</p>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  gap: 120px;
  justify-content: center;
  flex-wrap: nowrap;
  align-items: flex-start;
}

.card {
  width: 560px;
}

.cs-img {
  width: 560px;
  height: 400px;
}

.cs-date {
  width: 141px;
  height: 44px;
  margin: 0;

  font-family: "Poppins";
  font-style: italic;
  font-weight: 400;
  font-size: 15px;
  line-height: 44px;
  color: #03045e;
}

.cs-title {
  font-family: "Poppins";
  font-style: normal;
  margin: 0;
  font-weight: 600;
  font-size: 24px;
  line-height: 44px;
  color: #03045e;
}

.cs-description {
  width: 548px;
  height: 128px;
  margin: 0;
  padding-right: 12px;
  overflow: overlay;

  font-family: "Poppins";
  font-style: normal;
  text-align: justify;
  font-weight: 400;
  font-size: 18px;
  line-height: 32px;
  color: #03045e;
}

.scrollbar-style::-webkit-scrollbar-track {
  -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
  border-radius: 10px;
  background-color: #f5f5f5;
}

.scrollbar-style::-webkit-scrollbar {
  width: 12px;
  background-color: #f5f5f5;
}

.scrollbar-style::-webkit-scrollbar-thumb {
  border-radius: 10px;
  -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
  background-color: #555;
}
</style>
