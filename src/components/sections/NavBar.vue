<script setup lang="ts">
import NavLinks from "../molecules/NavLinks.vue";
import IconSocialBehance from "../icons/IconSocialBehance.vue";
import IconSocialMedium from "../icons/IconSocialMedium.vue";
import IconSocialTwitter from "../icons/IconSocialTwitter.vue";
</script>

<template>
  <div class="navbar-container">
    <span class="my-name">John Doe</span>

    <NavLinks :links="['Home', 'About', 'Work']" />

    <ul class="nav-icons">
      <li><IconSocialTwitter /></li>
      <li><IconSocialBehance /></li>
      <li><IconSocialMedium /></li>
    </ul>
  </div>
</template>

<style scoped>
.navbar-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 40px 0;
}

.my-name {
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;
}

.nav-icons {
  display: flex;
  gap: 29px;
}

.nav-icons li {
  font-weight: 400;
  font-size: 18px;
  line-height: 27px;
  list-style: none;
}
</style>
