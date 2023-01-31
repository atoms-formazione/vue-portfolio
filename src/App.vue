<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import AboutSection from './components/aboutSection.vue';
import ContactSection from './components/contactSection.vue';
import NavBar from './components/navbar.vue'
import theHero from './components/theHero.vue'
import WorkSection from './components/workSection.vue';

</script>

<template>
  <header>
    <NavBar></NavBar>
  </header>
  <body>
    <theHero></theHero>

    <AboutSection></AboutSection>
    
    <WorkSection></WorkSection>

    <ContactSection></ContactSection>
  </body>

  <RouterView />
</template>

<style scoped>

body{
  background-color: violet;
  color: darkblue ;

}
</style>
