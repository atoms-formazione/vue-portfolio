<template>
  <div class="mainIntro">
    <div class="container">
      <p>Hello, I'm Alessandro</p>
      <strong>Front-end Dev</strong>
      <p>based in Italy</p>
    </div>
    <div class="resume-download">
      <button class="resume-download-btn">Resume</button>
      <div class="resume-download-background"></div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.mainIntro {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding-left: 7.5rem;
  padding-top: 5.5rem;
  row-gap: 0.5rem;
}

.container {
  width: 100%;
}

.container strong {
  font-size: 7.5rem;
  font-weight: 800;
  text-align: center;
  line-height: 116%;
}

.container > p {
  font-size: 2.4rem;
  font-weight: bold;
  line-height: 3.8rem;
}

.resume-download-btn {
  position: relative;
  border: solid 1px #474306;
  border-radius: 6px;
  color: #474306;
  background-color: transparent;
  height: 4.2rem;
  width: 10rem;
  z-index: 1;
  font-size: 1.5rem;
}

.resume-download {
  height: fit-content;
  width: fit-content;
  position: relative;
}

.resume-download-background {
  border-radius: 6px;
  background: #f5ee84;
  height: 4.2rem;
  width: 10rem;
  position: absolute;
  top: 10.29%;
  left: 3.66%;
  z-index: 0;
}
</style>
