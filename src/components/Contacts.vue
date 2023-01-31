<script setup lang="ts"></script>

<template>
  <div class="contact">
    <img src="./icons/contact.svg" alt="contacts" class="img" />
    <div class="txt">
      <p class="text1">
        Lorem ipsum dolor sit amet, consectetur adipiscing<br />elit. Amet
        vulputate tristique quam felis. Id phasellus<br />dui orci vulputate
        consequat nulla proin. Id sit<br />scelerisque neque, proin bibendum
        diam.
      </p>
      <p class="text2">johndoe@mail.com</p>
      <p class="text2">twitter.com/johndoe</p>
      <p class="text2">behance.com/johndoe</p>
    </div>
  </div>
</template>

<style scoped>
.contact {
  display: flex;
}

.img {
  margin-left: 50px;
}

.text1,
.text2 {
  color: #03045e;
  font-size: 30px;
  margin-left: 5rem;
  margin-top: 0px;
}

.text2 {
  margin-bottom: 0px;
}
</style>
