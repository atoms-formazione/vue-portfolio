<script setup lang="ts">
// TODO: add links
</script>

<template>
  <div class="navbar-container">
    <span class="my-name">John Doe</span>

    <ul class="nav-links">
      <li>Home</li>
      <li>About</li>
      <li>Work</li>
    </ul>

    <ul class="nav-icons">
      <li>Icon1</li>
      <li>Icon2</li>
      <li>Icon3</li>
    </ul>
  </div>
</template>

<style scoped>
.navbar-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.my-name {
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;
}

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

.nav-icons {
  display: flex;
  gap: 29px;
}

.nav-icons li {
  font-weight: 400;
  font-size: 18px;
  line-height: 27px;
  list-style: none;
  border: solid black;
}
</style>
