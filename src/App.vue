<script setup lang="ts">
import AboutMe from "./components/AboutMe.vue";
import NavBar from "./components/NavBar.vue";
import TheHero from "./components/TheHero.vue";
import WorkSpace from "./components/WorkSpace.vue";
import Contatacs from "./components/Contatacs.vue";
</script>

<template>
  <div>
    <NavBar></NavBar>
    <TheHero></TheHero>
    <div class="midsection">
      <div class="about" id="aboutme"><AboutMe></AboutMe></div>
      <div class="workspace" id="workspace"><WorkSpace></WorkSpace></div>
    </div>
    <Contatacs id="contatti"></Contatacs>
  </div>
</template>

<style scoped>
.midsection {
  display: flex;
  margin-bottom: -150px;
}

.about {
  flex: 1;
}
.workspace {
  flex: 1;
}
</style>
