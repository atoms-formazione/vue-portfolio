<script setup lang="ts">
type WorkCardProps = {
  image: string;
  date: string;
  title: string;
  description: string;
};
defineProps<WorkCardProps>();
</script>

<template>
  <div class="card-container">
    <img :src="`/src/components/icons/${image}.png`">
    <h6>{{ date }}</h6>
    <h4>{{ title }}</h4>
    <p>{{ description }}</p>
  </div>
</template>

<style scoped>
img {
  object-fit: cover;
  width: 100%;
}
h6 {
  font-style: italic;
  font-weight: 400;
  font-size: 15px;
  line-height: 44px;
  color: #03045E;

}
h4 {
  font-weight: 600;
  font-size: 24px;
  line-height: 44px;
  color: #03045E;

}
p {
  font-weight: 400;
  font-size: 18px;
  line-height: 32px;
  color: #03045E;

}
</style>