<template>
  <div class="hero">
    <TheHeroWelcomeIntro> </TheHeroWelcomeIntro>

    <TheHeroBigAvatar> </TheHeroBigAvatar>
  </div>
</template>
<script setup lang="ts">
import TheHeroWelcomeIntro from "./TheHeroWelcomeIntro.vue";
import TheHeroBigAvatar from "./TheHeroBigAvatar.vue";
</script>
<style>
.hero {
  display: flex;
  margin: 2rem;
  max-width: 768px;
  gap: 10rem;
}
</style>
