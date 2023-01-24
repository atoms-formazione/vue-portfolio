<script setup lang="ts"></script>

<template>
  <div>
    <h1 class="name">John Doe</h1>
    <h1 class="navbar">home about work</h1>
    <img src="./icons/vector.svg" alt="vector" class="vector" />
    <img src="./icons/behance.svg" alt="behance" class="behance" />
    <img src="./icons/twitter.svg" alt="twitter" class="twitter" />
  </div>
</template>

<style scoped>
.name {
  position: absolute;
  width: 114px;
  height: 36px;
  left: 97px;
  top: 34px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;

  color: #03045e;
}

.navbar {
  position: absolute;
  width: 276px;
  height: 27px;
  left: 582px;
  top: 37px;
}

.vector {
  position: absolute;
  width: 26px;
  height: 15.05px;
  left: 1201px;
  top: 42px;
}

.behance {
  position: absolute;
  width: 26px;
  height: 16.1px;
  left: 1256px;
  top: 42px;
}

.twitter {
  position: absolute;
  width: 26px;
  height: 17.79px;
  left: 1311px;
  top: 41px;
}
</style>
