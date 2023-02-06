<script setup lang="ts"></script>

<template>
  <div>
    <h1 class="title">contact.</h1>
    <div class="contact">
    <img src="./icons/contact.png" class="img" />
    <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing<br />elit. Amet
        vulputate tristique quam felis. Id phasellus<br />dui orci vulputate
        consequat nulla proin. Id sit<br />scelerisque neque, proin bibendum
        diam.<br>
        johndoe@mail.com<br>
        twitter.com/johndoe<br>
        behance.com/johndoe<br>
      </p>
    </div>
  </div>
</template>

<style scoped>

 h1{
    font-size: 100px;
    color: #F7F197;
    margin-top: 17%;
}

p{
  font-family: 'Poppins';
   font-style: normal;
   font-weight: 400;
   font-size: 24px;
   line-height: 44px;
   color: #03045E;
   margin-left: 5rem;
  margin-top: 0px;
}
.img{
  margin-top: 10px;
  margin-left: 0.5rem;
}
.contact{
  display: flex;
}
</style>
