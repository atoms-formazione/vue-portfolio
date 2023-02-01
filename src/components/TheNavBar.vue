<script setup lang="ts"></script>

<template>
  <div class="topnav">
    <a>Lorenzo Boselli Botturi</a>
    <b href="url_home">Home</b>
    <b href="url_about">About</b>
    <b href="url_work">Work</b>
    <img id="icons" height="35" width="35" src="icon1.png" />
    <img id="icons" height="35" width="35" src="icon2.png" />
    <img id="icons" height="35" width="35" src="icon3.png" />
  </div>
</template>

<style scoped>
.topnav {
  font-family: "Courier New", Courier, monospace;
  font-size: 27px;
  overflow: hidden;
  width: 100%;
  display: flex;
  position: relative;
  font-weight: bold;
}

.topnav a {
  color: black;
  padding: 14px 16px;
  text-decoration: none;
  margin: 20px;
  position: relative;
  top: -20px;
  left: 0px;
}

.topnav b {
  color: black;
  padding: 14px 16px;
  text-decoration: none;
  position: relative;
  font-weight: normal;
  top: 0%;
  left: 16%;
  height: 29px;
  width: auto;
  border-radius: 10px;
}

.topnav b:hover {
  background-color: rgb(230, 225, 154);
}

.topnav #icons {
  position: relative;
  top: 16px;
  right: -38%;
}
.topnav #icons:hover {
  background-color: rgb(230, 225, 154);
  border-radius: 5px;
}
</style>
