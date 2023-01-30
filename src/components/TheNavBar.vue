<script setup lang="ts"></script>

<template>
  <div class="topnav">
    <a>Lorenzo B.B.</a>
    <b href="url_home">Home</b>
    <b href="url_about">About</b>
    <b href="url_work">Work</b>
  </div>
</template>

<style scoped>
.topnav {
  background-color: rgb(208, 208, 147);
  font-family: "Courier New", Courier, monospace;
  overflow: hidden;
  width: 100%;
  display: flex;
  display: flex;
  justify-content: center;
  position: relative;
  font-weight: bold;
}

.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
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
  font-size: 17px;
  text-align: center;
  position: relative;
  font-weight: normal;
}

.topnav b:hover {
  background-color: rgb(199, 199, 169);
}
</style>
