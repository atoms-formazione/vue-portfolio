<script setup lang="ts">
let jobList = [
  {
    date: "2014-2018",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. " +
      "Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
  {
    date: "2018-2020",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. " +
      "Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
  {
    date: "2020-Present",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. " +
      "Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.",
  },
];
</script>
<template>
  <div>
    <ul>
      <li v-for="(job, index) in jobList" :key="index">
        <h3 class="job-date">{{ job.date }}</h3>
        <p class="job-description">{{ job.description }}</p>
      </li>
    </ul>
  </div>
</template>
<style scoped>
div {
  display: flex;
  justify-content: center;
}

.job-date {
  width: 122px;
  height: 40px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 40px;
  color: #03045e;
}

.job-description {
  width: 900px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
  color: #03045e;
}

li {
  font-size: 30px;
}

@media screen and (max-width: 1050px) {
  div {
    flex-wrap: nowrap;
    margin: auto;
  }

  .job-description {
    width: 100%;
  }
}
</style>
