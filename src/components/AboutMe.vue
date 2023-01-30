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
                <li><h3>Competenze tecniche</h3><p>Competenze di base nella programmazione in backend con linguaggi come JAVA ed SQL, ed in frontend con linguaggio HTML, CSS e JAVASCRIPT, oltre al framework Angular</p></li>
                <br>
                <li><h3>Soft Skill</h3><p>Capacità di lavorare in team, agilità nella risoluzione dei problemi, duttilità nell'affrontare situazioni presenti nell'ambiente lavorativo,</p></li>
                <br>
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