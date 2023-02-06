<template>
    <div class="container">
        <p> John Doe </p>   
        <nav class="nav-bar">
        <a><RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/work">Work</RouterLink></a>
        </nav>
    <div class="icone">
        <img src="src/components/icons/medium-4 1.png"  />
        <img src="src/components/icons/Vector.png"/>
        <img src="src/components/icons/twitter-6 1.png"/>
    </div>
    </div>
</template>
<script setup lang="ts">

</script>
<style lang="css">

.container{
display: flex;
align-items: center;
padding: 1rem;
justify-content: space-between;
}

.container p{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 36px;
    color: #03045E;
}
.nav-bar a{
    text-decoration: none;
    color: #03045E;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 27px;
}
</style>