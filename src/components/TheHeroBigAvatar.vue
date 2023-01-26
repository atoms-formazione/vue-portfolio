<template>
  <div class="images">
    <img src="src/components/icons/Image.svg" class="big-avatar" />
    <img src="src/components/icons/Group 10.svg" class="big-avatar1" />
    <img src="src/components/icons/Group 6.svg" class="big-avatar2" />
  </div>
</template>
<script lang="ts">
export default {};
</script>
<style>
.big-avatar {
  padding-right: 0px;
  width: 306px;
  height: 309px;
}
.big-avatar1 {
  width: 50px;
  height: 56px;
 
  transform: translate(-10%, -200%);

}
.big-avatar2 {
  width: 103.85px;
  height: 29.44px;
  /* mix-blend-mode: color-burn; */
  transform: translate(-380%, 240%);
  background-color: transparent;
}
.images {
 display: flex;
 justify-content: center;
 align-items: center;
 width: 100px;
}
/* .big-avatar {
  padding-right: 0px;
  width: 306px;
  height: 309px;
  left: 831px;
  top: 191px;
} */
</style>
