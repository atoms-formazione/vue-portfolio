<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import WelcomeIntro from "./WelcomeIntro.vue";
import BigAvatar from "./BigAvatar.vue";
</script>

<template>
  <!-- the hero  -->
  <div>
    <WelcomeIntro id="introOrder"></WelcomeIntro>
    <BigAvatar id="imgOrder"></BigAvatar>
  </div>
</template>

<style scoped>
#introOrder {
  position: fixed;
  top: 21%;
  left: 4%;
}

#imgOrder {
  display: flex;
  float: right;
  position: fixed;
  top: 17%;
  right: 25%;
}
</style>
