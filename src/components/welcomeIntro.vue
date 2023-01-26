<template>
  <div class="container">
    <div class="testo">
      <p class="p">Hello, I'm Pietro</p>
      <strong class="job"> {{ job }} </strong>
      <p class="p">Based in Italy</p>
    <div class="buttondiv">
        <button class="buttonResume"><a href="@/assets/CV-StivanelloPietro.pdf" target="_blank">Resume</a></button>
    </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const job = "Software Developer";
</script>

<style scoped>

.buttondiv{
  background-color: rgba(255, 1, 208);
    width: 100%;
    margin-top: 2rem;
}

.buttondiv> button > a{
  text-decoration: none;
  padding:1rem;
  padding-left: 2rem;
  padding-right: 2rem;
}

.buttonResume{
    text-align: left;
    padding: 1rem;
    font-size: 1rem;
    background-color: rgb(247, 80, 217);
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
    height: 80vh;
    background-color: rgba(255, 1, 208);
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
  background-color: rgba(255, 1, 208);
  align-items: center;
  text-align: left;
  margin-left: 5%;
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
