<template>
    <div class="container">
        <strong class="sectionTitle"> {{ sectionTitle }} </strong>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, deleniti esse nesciunt, ducimus quam asperiores iure, laborum dolorum explicabo eaque vitae quisquam provident accusamus repellat eveniet impedit aut corrupti? Cumque.</p>
    </div>
</template>

<script setup lang="ts">
const sectionTitle = "about.";
</script>

<style scoped>
.sectionTitle{
    width: 100%;  
    font-size: 4rem;
    font-weight: 800;
    word-wrap: break-word;
    color: orangered;
}
.container{
  
margin-left: 5%;
margin-right: 5%;  
}

.container > p {
    font-size: 1.2rem;
}
</style>