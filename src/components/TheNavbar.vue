<script setup lang="ts"></script>

<template>
  <div class="all">
    <h1 class="name">John Doe</h1>
    <div class="centered">
      <h1 class="navbar">home</h1>
      <h1 class="navbar">about</h1>
      <h1 class="navbar">work</h1>
    </div>
    <div class="icons">
      <img src="./icons/vector.svg" alt="vector" class="vector" />
      <img src="./icons/behance.svg" alt="behance" class="behance" />
      <img src="./icons/twitter.svg" alt="twitter" class="twitter" />
    </div>
  </div>
</template>

<style scoped>
.all {
  display: flex;
  flex-direction: row;
  align-content: center;
}
.name {
  flex: 1;
  width: 114px;
  height: 36px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;

  color: #03045e;
}
.centered {
  flex: 1;
  display: flex;
}

.icons {
  flex: 0.5;
  display: flex;
  align-items: right;
}

.navbar {
  flex: 1;
  width: 276px;
  height: 27px;
  font-weight: 300;
  font-size: 24px;
  color: #03045e;
}

.vector {
  flex: 1;
  width: 26px;
  height: 15.05px;
}

.behance {
  flex: 1;
  width: 26px;
  height: 16.1px;
}

.twitter {
  flex: 1;
  width: 26px;
  height: 17.79px;
}
</style>
