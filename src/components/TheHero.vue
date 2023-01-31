<template>
  <div class="hero">
    <TheHeroWelcomeIntro class="intro"> </TheHeroWelcomeIntro>

    <TheHeroBigAvatar class="bigAvatar"> </TheHeroBigAvatar>
  </div>
</template>
<script setup lang="ts">
import TheHeroWelcomeIntro from "./TheHeroWelcomeIntro.vue";
import TheHeroBigAvatar from "./TheHeroBigAvatar.vue";
</script>
<style>
.hero {
  display: flex;
  justify-content: center;
  flex-wrap: nowrap;
  align-content: center;
  align-items: center;
  margin: 2rem;
  gap: 10rem
}
.bigAvatar, .intro{
  width: 458px;
}
</style>
