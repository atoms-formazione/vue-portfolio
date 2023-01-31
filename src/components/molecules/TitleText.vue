<script setup lang="ts">
type TitleTextProps = {
  title: string;
  text?: string;
};

defineProps<TitleTextProps>();
</script>

<template>
  <div>
    <h2>{{ title }}</h2>
    <p v-if="text">{{ text }}</p>
  </div>
</template>

<style scoped>
h2 {
  font-weight: 800;
  font-size: 100px;
  line-height: 116px;
  color: var(--yellow);
}

p {
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
  margin-top: 32px;
}
</style>
