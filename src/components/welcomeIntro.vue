<template>
  <div class="container">
    <div class="testo">
      <p class="p">Hello, I'm Pietro</p>
      <strong class="job"> {{ job }} </strong>
      <p class="p">Based in Italy</p>
    <div class="buttondiv">
        <button class="buttonResume">Resume</button>
    </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const job = "Software Developer";
</script>

<style scoped>

.buttondiv{
    background-color: rebeccapurple;
    width: 100%;
    margin-top: 2rem;
}
.buttonResume{
    text-align: left;
    padding: 1rem;
    background-color: aquamarine;
    border-radius: 10px;
    width: 164px;
    height: 68px;
    display: block;
    position: relative;
    text-align: center;
    justify-content:center;
}
.container{
    width: 50vw;
    height: 90vh;
    background-color: blue;
    display: flex;
    justify-content: center;

}
.p {
  text-align: left;
  width: 100%;
  font-weight: 500;
 font-size: 1.2rem;
}
.testo {
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: aqua;
  align-items: center;
  text-align: left;
}
.job {
  width: 100%;  
  font-size: 4rem;
  font-weight: 800;
  word-wrap: break-word;
}
/* .job::before {
  content: "Hello, I'm Pietro";
  font-size: 1rem;
}
.job::after {
  content: "Based in Italy";
  font-size: 1rem;
} */
</style>
