<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/navbar.vue'
import theHero from './components/theHero.vue'

</script>

<template>
  <header>
    <NavBar></NavBar>
  </header>
  <body>
    <theHero></theHero>
  </body>

  <!-- <RouterView /> -->
</template>

<style scoped>

body{
  background-color: antiquewhite;
  color: darkblue ;

}
</style>
