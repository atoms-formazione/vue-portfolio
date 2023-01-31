<script setup lang="ts"></script>

<template>
  <div class="WI">
    <p class="left">Hi, i'm Lorenzo,</p>
    <p class="left" id="big">Junior Web Developer</p>
    <p class="left">Based in Italy.</p>
    <button class="left" id="buttonResume">Resume</button>
  </div>
</template>

<style scoped>
.WI {
  font-family: "Courier New", Courier, monospace;
  font-size: 30px;
  font-weight: normal;
  color: black;
  position: relative;
}

.left {
  margin-left: 18%;
}

#big {
  font-weight: bold;
  font-size: 45px;
}

#buttonResume {
  background-color: rgb(196, 196, 134);
  border-radius: 6px;
  border-color: rgb(152, 152, 152);
}
</style>
