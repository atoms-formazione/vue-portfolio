<template>
    <div class="listJob">
        <ul>
            <li> <span>{{ date1 }}</span> <p>{{ job1 }}</p> </li>
            <li> <span>{{ date2 }}</span> <p>{{ job2 }}</p> </li>
            <li> <span>{{ date3 }}</span><p>{{ job3 }}</p> </li>
        </ul>
    </div>
</template>
<script setup lang="ts">
    const date1 = "2014-2018";
    const date2 = "2018-2020";
    const date3 = "2020-Present";
    const job1 = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.";
    const job2 = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.";
    const job3 = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate tristique quam felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.";

</script>
<style>
    .listJob{
        padding-left: 200px;
        margin-top: 2rem;
        padding-top: 50px;
        font-weight: 400;
        font-size: 24px;
    }
    span{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: bold;
        color: #03045E;    
    }
   li p{
        font-family: 'Poppins';
        font-style: normal;
        color: #03045E;
        transform: translate(-.5%);
        padding-top: 1.5rem;
        padding-bottom: 3.5rem;
    }

</style>