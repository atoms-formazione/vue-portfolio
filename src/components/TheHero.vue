<script setup lang="ts">
import WelcomeIntro from "./WelcomeIntro.vue";
import BigAvatar from "./BigAvatar.vue";
</script>

<template>
  <div class="hero">
    <WelcomeIntro></WelcomeIntro>
    <BigAvatar></BigAvatar>
  </div>
</template>

<style>
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 50px;
}
</style>
