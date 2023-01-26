<template>
    <div class="avatar-img">
            <img src="@/assets/Immagine.jpg" alt="Avatar">
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

.avatar-img{
    width: 48vw;
    height: 80vh;
    margin-right: 5%;
}

.avatar-img>img{
    max-width:70%;
    max-height:70%;
  
    position:absolute;
    text-align: center;
    border-radius: 50%;
    margin: 5rem;
    margin-left: 10rem;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>