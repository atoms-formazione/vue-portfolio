<script setup lang="ts">
import WelcomeIntro from "./WelcomeIntro.vue";
import BigAvatar from "./BigAvatar.vue";
</script>

<template>
  <div>
    <WelcomeIntro id="introOrder"></WelcomeIntro>
    <BigAvatar id="imgOrder"></BigAvatar>
  </div>
</template>

<style scoped>
#introOrder {
  position: relative;
  top: 70px;
  width: 85%;
}

#imgOrder {
  display: flex;
  float: right;
  position: relative;
  top: -215px;
  right: 13%;
}
</style>
