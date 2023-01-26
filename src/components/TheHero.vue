<template >
    <div  class="TheHero">
        <WelcomeIntro></WelcomeIntro>  
        <BigAvatar></BigAvatar>
    </div>
</template>
<script setup lang="ts" >
import WelcomeIntro from './WelcomeIntro.vue';
import BigAvatar from './BigAvatar.vue';
</script>
<style lang="css">
 .TheHero{
    display: flex;
 }
</style>