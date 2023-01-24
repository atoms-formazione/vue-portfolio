<template>
  <div class="mainAvatar">
    <div class="vector">
      <img src="../assets/FOTODUDO.svg" />
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.mainAvatar {
  background-color: red;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}

.vector {
  border: solid 1px #474306;
  overflow: hidden;
  border-radius: 50%;
}

img {
  height: auto;
}
</style>
