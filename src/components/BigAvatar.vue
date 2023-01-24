<script setup lang="ts">
defineProps<{
  imgPath: string;
}>();
</script>
<template>
  <div>
    <div>
      <img class="big-avatar" src="./imgs/BigAvatar.svg" alt="big-avatar-img" />
      <img
        id="big-avatar-decoration-1"
        src="./imgs/BigAvatarDecoration1.svg"
        alt="big-avatar-decoration-1"
      />
      <img
        id="big-avatar-decoration-2"
        src="./imgs/BigAvatarDecoration2.svg"
        alt="big-avatar-decoration-2"
      />
    </div>
  </div>
</template>
<style scoped>
.big-avatar {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 500px;
  height: 500px;
}

#big-avatar-decoration-1 {
  position: relative;
  bottom: 160px;
  right: 10px;
  z-index: 2;
}

#big-avatar-decoration-2 {
  position: relative;
  bottom: 500px;
  left: 350px;
  z-index: 2;
}
</style>
