<template>
    <div class="AboutSection">
        <div class="Title">
            <h1>about me.</h1>
        </div>
        <div class="description">
            <p>
                Focus principale del mio carattere è la grinta e disciplina, 
                dinamico in ogni aspetto lavorativo e non, empatico, 
                buone capacità nel relazionarmi con persone e ambiente esterno.
            </p>
        </div>
        <div class="JobList">
            <ul>
                <li><p>lavoro di squadra</p></li>
                <li><p>empatia</p></li>
                <li><p>coraggio</p></li>
            </ul>
        </div>
    </div>
</template>

<script setup lang="ts">
 
</script>

<style scoped>
    div{
        color: #14213d;
    }

    .AboutSection{
        margin-left: 1rem;
        margin-top: 2rem;
        padding: 4rem;
    }

    .title{
        margin: 2rem;
    }
     h1 {
        font-size: 3rem;
        font-weight: bolder;
        color: #fca311;
    }

    .description {
        display: flex;
        flex: 1/2;

    }

    .JobList {
        margin-left: 2rem;
        margin-top: 2rem;
    }

</style>