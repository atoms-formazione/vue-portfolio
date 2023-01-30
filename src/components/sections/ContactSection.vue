<script setup lang="ts">
import TitleText from "../molecules/TitleText.vue";

const titleText = {
  title: "contact.",
};
</script>

<template>
  <div class="contact-container">
    <TitleText v-bind="titleText" />

    <div class="image-text-container">
      <img src="static/images/contact.png" alt="A pen" />

      <div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis
          praesentium alias provident, ad molestias sit reprehenderit autem,
          ducimus, laborum velit voluptatem a voluptatum iusto. Natus fuga
          eligendi sed iusto maxime.
        </p>

        <ul>
          <li>contact1</li>
          <li>contact2</li>
          <li>contact3</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
.contact-container {
  margin-top: 200px;
}

.title-section {
  margin-bottom: 145px;
}
.image-text-container {
  display: flex;
  gap: 60px;
  margin-top: 50px;
}

p {
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
}
li {
  font-weight: 400;
  font-size: 24px;
  line-height: 44px;
  list-style: none;
}
</style>
