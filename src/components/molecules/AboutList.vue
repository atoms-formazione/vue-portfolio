<script setup lang="ts">
type Experience = {
  duration: string;
  description: string;
};

type AboutListProps = {
  list: Experience[];
};

defineProps<AboutListProps>();
</script>

<template>
  <div>
    <ul>
      <li v-for="{ duration, description } in list" :key="duration">
        <h3>{{ duration }}</h3>
        <p>{{ description }}</p>
      </li>
    </ul>
  </div>
</template>

<style scoped>
li {
  margin-bottom: 80px;
}

h3 {
  font-weight: 600;
  font-size: 24px;
  line-height: 40px;
}

p {
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
}
</style>
