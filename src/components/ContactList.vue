<script setup lang="ts"></script>
<template>
  <div class="container">
    <img class="contact-img" src="../assets/ContactSec.svg" alt="contact-sec-img" />
    <div class="contact-container">
      <p class="contact-desc">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique
        quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit
        scelerisque neque, proin bibendum diam.
      </p>
      <ul>
        <li>johndoe@mail.com</li>
        <li>twitter.com/johndoe</li>
        <li>behance.com/johndoe</li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
li {
  list-style-type: none;
}

.contact-img {
  width: 440px;
  height: 314px;
}

.contact-desc {
  width: 640px;
  height: 176px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
  color: #03045e;
}

.container {
  display: flex;
  gap: 60px;
  width: 1240px;
  margin: 50px auto 100px auto;
}

.container > img {
  padding-top: 6px;
}

.contact-container {
  display: flex;
  flex-direction: column;
}

.contact-container > ul {
  padding-left: 0;
  margin: 0;
}

.contact-container > p {
  margin-top: 0;
  margin-bottom: 10px;
}

li {
  width: 246px;
  height: 44px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
  color: #03045e;
}
</style>
