<script setup lang="ts">
import BigAvatar from "./BigAvatar.vue";
import WelcomeIntro from "./WelcomeIntro.vue";

const p1 = defineProps<{
  firstName: string;
  residency: string;
  employment: string;
  imgPath: string;
}>();
</script>

<template>
  <div id="the-hero-section">
    <!--<WelcomeIntro
      class="welcome-component"
      firstName="John"
      residency="Nederland"
      employment="Product Designer"
    ></WelcomeIntro>-->
    <WelcomeIntro class="welcome-component" v-bind="p1"></WelcomeIntro>
    <BigAvatar class="big-avatar-component" :imgPath="imgPath"></BigAvatar>
  </div>
</template>

<style scoped>
div {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
  align-content: center;
  margin-top: 40px;
}

.welcome-component,
.big-avatar-component {
  width: 600px;
  height: 600px;
}
</style>
