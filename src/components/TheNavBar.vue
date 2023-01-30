<script setup lang="ts"></script>

<template>
  <div class="topnav">
    <b>Lorenzo B.B.</b>
    <a href="url_home">Home</a>
    <a href="url_about">About</a>
    <a href="url_work">Work</a>
  </div>
</template>

<style scoped>
.topnav {
  background-color: rgb(208, 208, 147);
  overflow: hidden;
  width: 100%;
}

.topnav b {
  float: left;
  color: black;
  text-align: left;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  margin: 20px;
}

.topnav a {
  float: left;
  color: black;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  text-align: right;
}

.topnav a:hover {
  background-color: rgb(207, 207, 198);
}
</style>
