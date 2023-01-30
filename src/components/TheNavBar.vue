<script setup lang="ts"></script>

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
  background-color: rgb(208, 208, 147);
  font-family: "Courier New", Courier, monospace;
  font-size: 20px;
  overflow: hidden;
  width: 100%;
  display: flex;
  display: flex;
  justify-content: center;
  position: relative;
  font-weight: bold;
  float: left;
}

.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  margin: 20px;
  position: fixed;
  top: -12px;
  left: 0px;
}

.topnav b {
  float: left;
  color: black;
  padding: 14px 16px;
  text-decoration: none;
  text-align: center;
  position: relative;
  font-weight: normal;
}

.topnav b:hover {
  background-color: rgb(199, 199, 169);
}

.icons {
  float: left;
  position: fixed;
  top: 21px;
  right: 45px;
}
.icons :hover {
  background-color: rgb(196, 196, 167);
}
</style>
