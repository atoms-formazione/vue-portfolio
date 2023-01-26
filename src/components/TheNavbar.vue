<script setup lang="ts">
import { RouterLink } from "vue-router";

defineProps<{
  firstName: string;
  lastName: string;
}>();
</script>

<template>
  <div class="container">
    <span class="nav-intro">{{ firstName }} {{ lastName }}</span>
    <nav class="nav-menu">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/work">Work</RouterLink>
    </nav>
    <nav class="nav-social">
      <a href="#"><img src="./icons/Vector.png" alt="nav-twitter" /></a>
      <a href="#"><img src="./icons/behance-2 1.png" alt="nav-twitter" /></a>
      <a href="https://twitter.com/"
        ><img src="./icons/icons8-twitter-60.png" alt="nav-twitter"
      /></a>
    </nav>
  </div>
</template>

<style scoped>
.container {
  padding: 20px;
  display: flex;
  place-items: flex-start;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
}

.nav-intro {
  width: 114px;
  height: 36px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;
  color: #03045e;
}

.nav-menu {
  font-size: 18px;
  width: 276px;
  height: 27px;

  display: flex;
  gap: 20px;
  justify-content: space-between;
}

.nav-menu > a {
  width: 54px;
  height: 27px;
  text-align: center;
  text-decoration: none;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 27px;

  color: #03045e;
}

.nav-social {
  font-size: 18px;
  text-align: end;

  display: flex;
  gap: 20px;
  justify-content: space-between;
  align-items: center;
}

.nav-social > a > img {
  width: 26px;
}
</style>
