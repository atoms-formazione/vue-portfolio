<template>
      <div class="flex-container">
        
        <div class="titleText" id="about">
            <TitleText></TitleText>
        </div>
        <div class="jobList">
            <JobList></JobList>
        </div>
    </div>
</template>

<script setup lang="ts">
import JobList from './jobList.vue';
import TitleText from './titleText.vue';


</script>

<style scoped>
.flex-container{
    background-color: violet;

}
</style>