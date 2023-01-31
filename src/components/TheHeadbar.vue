<template>
  <div class="all">
    <TheHeadBarLeft></TheHeadBarLeft>
    <TheHeadBarCenter></TheHeadBarCenter>
    <TheHeadBarRight></TheHeadBarRight>
  </div>
</template>

<script setup lang="ts">
import TheHeadBarCenter from "./TheHeadBarCenter.vue";
import TheHeadBarLeft from "./TheHeadBarLeft.vue";
import TheHeadBarRight from "./TheHeadBarRight.vue";
</script>

<style scoped>
.all {
  width: 100vw;
  height: 15vh;
  position: absolute;
  top: 0;
  left: 0;
  display: flex;
  padding: 1.8rem 5rem 1rem 2rem;
  gap: 16vw;
  position: static;
  justify-content: space-between;
}
</style>
