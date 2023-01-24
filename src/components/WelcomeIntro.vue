<template>
  <div class="mainIntro">
    <div class="container">
      <p>Hello I'm a monke</p>
      <strong>Uh-oh stinky!</strong>
      <p>Based in Italy</p>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.mainIntro {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  width: 100%;
}

.container strong {
  font-size: 5rem;
  font-weight: 800;
  text-align: center;
}

.container p {
  text-align: center;
}
</style>
