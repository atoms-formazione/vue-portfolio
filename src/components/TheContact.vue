<template>
  <div class="contact">
    <h1>{{ titre }}</h1>
  </div>
  <div class="contactElec">
    <div>
      <img src="src\components\icons\workCase2.svg" />
    </div>
    <div class="texteContact">
      <p>{{ texte }}</p>
      <a href="johndoe@mail.com">johndoe@mail.com</a> <br>
      <a href="http:/twitter.com/johndoe">twitter.com/johndoe</a><br>
      <a href="http:/behance.com/johndoe">behance.com/johndoe</a>
    </div>
  </div>
</template>
<script setup lang="ts">
import { ref } from "vue";
const titre = ref("contact.");
const texte = ref(
  "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam."
);
</script>
<style>
    .contact h1 {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 800;
  font-size: 100px;
  color: #f7f197;
  padding: 0px 30px;
}
    .contactElec{
        display: flex;
        flex-direction: row;
        gap: 2rem;
    }
    .contactElec img{
        margin-left: 2rem;
        width: 440px;
        height: 314px;
        margin-top: -80px;
    }
    .texteContact a{
        text-decoration: none;
        cursor: pointer;
        font-family: "Poppins";
        color: #03045e;
        margin-bottom: -17px;
    }
    .texteContact{
        display: flex;
        flex-direction: column;
        /* justify-content: space-between; */
    }
    .texteContact p{
        font-family: "Poppins";
        font-style: normal;
        color: #03045e;
        margin-bottom: 60px;
    }
</style>
