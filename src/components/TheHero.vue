<template>
  <div class="main">
    <WelcomeIntro></WelcomeIntro>
    <BigAvatar></BigAvatar>
  </div>
</template>

<script setup lang="ts">
import BigAvatar from "./BigAvatar.vue";
import WelcomeIntro from "./WelcomeIntro.vue";
</script>

<style lang="css" scoped>
.main {
  width: 100vw;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-auto-flow: column;
  height: 47vw;
  position: static;
}
</style>
