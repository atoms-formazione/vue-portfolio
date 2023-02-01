<script setup lang="ts">
//
</script>

<template>
  <div id="img">
    <img id="caseImg1" height="270" width="400" src="caseExample1.png" />
    <img id="caseImg2" height="270" width="400" src="caseExample2.png" />
    <p id="caseTitle1">November 14, 2019</p>
    <p id="caseTitle2">November 28, 2019</p>
    <p id="caseTxt1"> <h1>Some Case Study</h1>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate
      tristique quam felis. Id phasellus dui orci vulputate consequat nulla
      proin. Id sit scelerisque neque, proin bibendum diam. </p>
    <p id="caseTxt2"> <h1>Some Case Study</h1>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate
      tristique quam felis. Id phasellus dui orci vulputate consequat nulla
      proin. Id sit scelerisque neque, proin bibendum diam.
    </p>
  </div>
</template>

<style scoped>
#img {
  font-family: "Courier New", Courier, monospace;
  font-size: 14px;
}
#caseImg1 {
  border-radius: 10px;
}
#caseImg2 {
  border-radius: 10px;
  position: relative;
  left: 800px;
  bottom: 274px;
}
#caseTitle1 {
  position: relative;
  bottom: 291px;
  left: 3px;
}
#caseTitle2 {
  position: relative;
  bottom: 321px;
  left: 803px;
}
#caseTxt1 {
  position: relative;
  bottom: 349px;
  padding-right: 220px;
}
h1 {
    position: relative;
    bottom: -15px;
}
#caseTxt2 {
  position: relative;
  bottom: 499px;
  left: 800px;
  padding-right: 220px;
}
</style>
