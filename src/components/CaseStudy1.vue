<script setup lang="ts"></script>

<template>
  <div>
    <img src="./icons/case1.svg" alt="case" class="case" />
    <p class="date">November 24, 2019</p>
    <p class="title">Some Case Study</p>
    <p class="text">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed<br />aliquam
      sollicitudin rhoncus morbi. Tincidunt quam sem elit a<br />convallis. Eget
      ipsum, velit vitae eu nunc, consequat, at.
    </p>
  </div>
</template>

<style scoped>
.case {
  width: 560px;
  height: 400px;
}

.date {
  font-style: oblique;
  font-size: small;
  color: #03045e;
}

.title {
  font-weight: bold;
  font-size: larger;
  color: #03045e;
}

.text {
  font-size: large;
  color: #03045e;
  margin-left: 0px;
}
</style>
