<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/sections/NavBar.vue";
</script>

<template>
  <header><NavBar /></header>

  <RouterView />
</template>
