<script setup lang="ts">
import IconAvatarLines from "./icons/IconAvatarLines.vue";
import IconAvatarPlus from "./icons/IconAvatarPlus.vue";
</script>

<template>
  <div class="container-presentation">
    <div class="presentaion-text">
      <h4>Hello, I'm John</h4>
      <h1>Product Designer</h1>
      <h4>based in Netherland.</h4>

      <button>Resume</button>
    </div>

    <div class="avatar-container">
      <img src="static/images/my-avatar.png" alt="A photo of me" />
      <IconAvatarLines class="icon-lines" />
      <IconAvatarPlus class="icon-plus" />
    </div>
  </div>
</template>

<style scoped>
.presentaion-text h1 {
  font-weight: 800;
  font-size: 100px;
  line-height: 116px;
}
.presentaion-text h4 {
  font-weight: 500;
  font-size: 28px;
  line-height: 42px;
}
.presentaion-text button {
  border: var(--dark-brown) solid;
  color: var(--dark-brown);
  background-color: transparent;
  border-radius: 6px;
  padding: 16px 45px;
  font-weight: 400;
  font-size: 20px;
  line-height: 30px;
  position: relative;
  margin-top: 42px;
}

.presentaion-text button::before {
  background-color: var(--yellow);
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  content: "";
  border-radius: 6px;
  padding: 16px 45px;
  z-index: -1;
  transform: translate(6px, 7px);
}
.container-presentation {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  height: 600px;
}

.icon-lines {
  position: absolute;
  bottom: 130px;
  left: 0;
}

.icon-plus {
  position: absolute;
  top: 0;
  right: 0;
}

img {
  width: 506px;
  height: 509px;
}
</style>
