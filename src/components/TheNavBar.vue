<template>
    <div class="container">
     <p> John Doe </p>   
         <div class="nav-bar">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink  to="/work">Work</RouterLink>
    </div>
    <div class="icone">
        <img src="src/components/icons/medium-4 1.png" class="img1" />
        <img src="src/components/icons/Vector.png"  class="img2">
        <img src="src/components/icons/twitter-6 1.png" class="img3">
    </div>
    </div>
</template>
<script setup lang="ts">

</script>
<style scoped>
.p{

width: 54px;
height: 27px;
left: 582px;
top: 37px;

font-family: 'Poppins';
font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 27px;

color: #03045E;
}
.nav-bar{

width: 276px;
height: 27px;
left: 623px;
top: 38px;

}
.container{
display: flex;
align-items: center;
padding: 1rem;
justify-content: space-between;
}

.img1{
width: 29px;
height: 16.1px;
}
.img2{
width: 26px;
height: 16.1px;

}
.img3{
width: 26px;
height: 16.1px;
justify-content: end;
}
.icone{
    flex: 0.5;
    
}
</style>