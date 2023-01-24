<script setup lang="ts"></script>

<template>
  <div>
    <h1 class="text1">Hello, I'm John,</h1>
    <h1 class="text2">Product<br />Designer</h1>
    <h1 class="text3">based in Netherland</h1>
    <button class="button">Resume</button>
  </div>
</template>

<style scoped>
.text1 {
  width: 211px;
  height: 42px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 42px;

  color: #03045e;

  margin-top: 0px;
  margin-bottom: 0px;
}

.text2 {
  width: 616px;
  height: 232px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 800;
  font-size: 100px;
  line-height: 116px;

  color: #03045e;

  margin-top: 0px;
  margin-bottom: 0px;
}

.text3 {
  width: 294px;
  height: 42px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 42px;

  color: #03045e;

  margin-top: 0px;
}

.button {
  width: 164px;
  height: 68px;
  background-color: #f5ee84;
  border-radius: 10px;
  font-size: large;
  box-shadow: 10px 10px #fbf8cc inset, 10px 10px #f5ee84;
}

.button:hover {
  cursor: pointer;
}
</style>
