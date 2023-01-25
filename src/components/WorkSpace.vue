<template>
    <div class="WorkSection">
        <div class="title">
            <h1>work.</h1>
            <p>Descrizione a random che non ho voglia di fare per ora, spero di ricordarmi di cambiarla prima di committare il progetto</p>
        </div>
        <div class="container">
            <div class="pic1">
              <img id="motard" src="https://www.quotidianomotori.com/wp-content/uploads/2020/09/11/07/30/KTM-450-SMR-2021-Title.jpg"/>
                <div>
                    <p>
                        inserire una foto qui sopra, qualcosa di interessante
                    </p>
                </div>
            </div>
            <div class="pic2">
              <img id="sport" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRWznen7CHpNwYax6274Llz9zEixvXxSntCMw&usqp=CAU"/>
                <div>
                    <p>
                        anchhe qui inserisci qualcosa di interessante tanto metterai un gatto o una foca arcobaleno
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
div {
    color: #14213d
}

.WorkSection {
    margin-left: 1rem;
        margin-top: auto;
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

.container{
    display: flex;
    margin: auto;
    padding: 1rem;
}

.pic1 {
    flex: 1;
    margin: 1rem;
}
.pic2 {
    flex: 1;
    margin: 1rem;
}

#motard {
    width: 100%;
    height: auto;
}

#sport {
    width: 113%;
    height: auto;
}
</style>