<script setup lang="ts">
//
</script>

<template>
  <div>
    <p id="bigContact">Contact.</p>
    <img id="contactImg" height="200" width="220" src="Contact.png" />
    <p id="contactText">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate
      tristigue quam felis. phasellus dui orci vulputate consequat nulla proin.
      Id sit scelerisque neque, proin bibendum diam. <br />
      <br />
      <br />
      <p id="contactInfo"> 
      Lorenzob@mail.com <br />
      instagram.com/Lorenzob <br />
      facebook.com/Lorenzob <br />
      </p>
    </p>
  </div>
</template>

<style scoped>
#bigContact {
  font-family: fantasy;
  font-size: 50px;
  color: rgb(196, 196, 134);
  float: left;
  position: relative;
  bottom: 175px;
  left: 35px;
  text-decoration: underline;
}
#contactImg {
  position: relative;
  border-radius: 10px;
  left: -136px;
  bottom: 35px;
}
#contactText {
  font-family: "Courier New", Courier, monospace;
  font-size: 18px;
  position: relative;
  left: 280px;
  bottom: 240px;
  padding-right: 550px;
}
#contactInfo {
    position: relative;
    bottom: 10px;
    font-weight: bold;
}
</style>
