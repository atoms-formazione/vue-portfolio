<template>
    <div class="flex-container">
        
        <div class="intro">
            <WelcomeIntro></WelcomeIntro>
        </div>
        <div class="avatar">
            <BigAvatar></BigAvatar>
        </div>
    </div>
</template>

<script setup lang="ts">
import BigAvatar from './bigAvatar.vue';
import WelcomeIntro from './welcomeIntro.vue';


</script>

<style scoped>
.flex-container{
    display: flex;
    margin-top: 3rem;
    
}
.intro{
    flex: 1;
}
.avatar{
    flex: 1;
    text-align: center;
    background-color: violet;
}
</style>