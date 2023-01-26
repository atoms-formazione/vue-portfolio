<template>
  <div class="description">
    <p class="greetting">Hello, I’m John,</p>
    <h3 class="profession">Product Designer</h3>
    <p class="local">based in Netherland.</p>
    <button>Resume</button>
  </div>
</template>
<script lang="ts">
export default {};
</script>
<style>
.description {
  font-family: "Poppins";
  font-style: normal;
  color: #03045e;
  display: flex;
  flex-direction: column;
  line-height: 70px;
  word-spacing: 10px;
}
.profession {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 70px;
  padding: 0px 20px;
 /*  line-height: 70px; */
  /* or 116% *
  /* Dark Blue */
  color: #03045e;
}
p{
  margin: 0;
}
.local {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  color: #03045e;
  transform: translate(0%,-70%);
}
.greetting {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  color: #03045e;
  transform: translate(0%,70%);
}
button {
  width: 164px;
  height: 68px;
  background-color: #F5EE84;
  transform: translate(15%);
  cursor: pointer;
}
</style>
