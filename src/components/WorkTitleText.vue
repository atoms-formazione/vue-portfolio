<script setup lang="ts"></script>
<template>
  <div>
    <h1>work.</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique
      quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit
      scelerisque neque, proin bibendum diam.
    </p>
  </div>
</template>
<style scoped>
h1 {
  width: 341px;
  height: 116px;
  margin-bottom: 0;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 800;
  font-size: 100px;
  line-height: 116px;
  color: #f7f197;

  display: flex;
  align-items: flex-end;
}

p {
  width: 900px;
  height: 132px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
  color: #03045e;
}

div {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-content: center;
  flex-wrap: wrap;

  margin-top: 100px;
  margin-right: 300px;
}

@media screen and (max-width: 1252px) {
  div {
    flex-wrap: nowrap;
    margin: auto;
  }
}
</style>
