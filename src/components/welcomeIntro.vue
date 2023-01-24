<template>
  <div>
    <strong class="job"> {{ job }} </strong>
  </div>
</template>

<script setup lang="ts">
const job = "Software Developer";
</script>

<style scoped>
.job {
  font-size: 4rem;
}
.job::before {
  content: "Hello, I'm Pietro";
  font-size: 1rem;
}
.job::after {
  content: "Based in Italy";
  font-size: 1rem;
}
</style>
