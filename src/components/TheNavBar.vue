<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="topnav">
    <a>Lorenzo Boselli Botturi</a>
    <b href="url_home">Home</b>
    <b href="url_about">About</b>
    <b href="url_work">Work</b>
    <div class="icons">
      <img height="24" width="24" src="icon1.png" />
      <img height="24" width="24" src="icon2.png" />
      <img height="24" width="24" src="icon3.png" />
    </div>
  </div>
</template>

<style scoped>
.topnav {
  font-family: "Courier New", Courier, monospace;
  font-size: 25px;
  overflow: hidden;
  width: 100%;
  display: flex;
  justify-content: center;
  position: relative;
  font-weight: bold;
}

.topnav a {
  color: black;
  padding: 14px 16px;
  text-decoration: none;
  margin: 20px;
  position: fixed;
  top: -12px;
  left: 0%;
}

.topnav b {
  color: black;
  padding: 14px 16px;
  text-decoration: none;
  text-align: center;
  position: relative;
  font-weight: normal;
}

.topnav b:hover {
  background-color: rgb(230, 225, 154);
}

.icons {
  position: fixed;
  top: 21px;
  right: 45px;
}
.icons :hover {
  background-color: rgb(196, 196, 167);
}
</style>
