<script setup lang="ts">
defineProps<{
  firstName: string;
  residency: string;
  employment: string;
}>();
</script>
<template>
  <div>
    <div>
      <div class="container-intro">
        <h3>Hello, I'm {{ firstName }},</h3>
        <h1>{{ employment }}</h1>
        <p>based in {{ residency }}.</p>
      </div>
      <button id="btn-resume">Resume</button>
    </div>
  </div>
</template>
<style scoped>
.container-intro {
  color: #03045e;
}

#btn-resume {
  width: 158px;
  height: 62px;
  color: #474306;
  font-size: 20px;
  margin-top: 38px;
  margin-left: 10px;

  display: block;
  position: relative;
  z-index: 1;
  cursor: pointer;

  border: none;
  outline: #474306 solid 1px;
  border-radius: 6px;
  background-color: transparent;
}

#btn-resume::before {
  content: "";
  border-radius: 6px;
  position: absolute;
  display: block;
  bottom: -6px;
  left: 6px;
  width: 158px;
  height: 62px;
  z-index: -1;
  background-color: #f5ee84;
  outline: #f5ee84 1px solid;
}

#btn-resume:active {
  transform: translate(6px, 6px);
}
#btn-resume:active::before {
  transform: translate(-6px, -6px);
}

.container-intro > h1 {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 800;
  font-size: 100px;
  line-height: 116px;
  margin: 10px;

  display: flex;
  align-items: flex-end;
}

.container-intro > p,
.container-intro > h3 {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 42px;
  margin: 10px;
}
</style>
