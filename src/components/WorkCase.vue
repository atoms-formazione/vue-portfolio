<template>
  <div class="cas">
    <div class="case1">
      <img src="src/components/icons/workCase1.svg" />
      <h5>{{ jour }}</h5>
      <h3>{{ titre }}</h3>
      <p>{{ texte }}</p>
    </div>
    <div class="case2">
      <img src="src\components\icons\contactSect.svg" />
      <h5>{{ jour }}</h5>
      <h3>{{ titre }}</h3>
      <p>{{ texte }}</p>
    </div>
  </div>
</template>
<script setup lang="ts">
import { ref } from "vue";
const jour = ref("November 24, 2019");
const titre = ref("Some Case Study");
const texte = ref(
  "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a convallis. Eget ipsum, velit vitae eu nunc, consequat, at."
);
</script>
<style>
.cas{
  display: flex;
  flex-direction: row;
  gap: 1rem;
  justify-content: center;
  align-items: center;
  margin-top: 60px;
  margin-left: 2rem;
  font-family: "Poppins";
  font-style: normal;
  color: #03045e;
  text-align: justify;
}
.case2{
    width: 50%;
    margin-left: 8rem;
    text-align: justify;
    position: relative;
    left: -90px;
}
.case1{
  text-align: justify;
  margin-right: 13rem;
  width: 50%;
}
.case1,.case2 p{
    width: 100%;
}
.case1 h5,.case2 h5{
  margin-top: 1px;
  font-style: italic;
}

</style>
