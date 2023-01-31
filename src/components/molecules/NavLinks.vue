<script setup lang="ts">
type NavLInksProps = {
  links: string[];
};

defineProps<NavLInksProps>();
</script>

<template>
  <ul class="nav-links">
    <li v-for="link in links" :key="link">
      <a href="#">{{ link }}</a>
    </li>
  </ul>
</template>

<style scoped>
.nav-links {
  display: flex;
  gap: 61px;
}

.nav-links li {
  font-weight: 400;
  font-size: 18px;
  line-height: 27px;
  list-style: none;
}

.nav-links li a {
  text-decoration: none;
  color: var(--dark-blue);
}
</style>
