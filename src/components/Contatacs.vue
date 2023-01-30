<!-- eslint-disable vue/multi-word-component-names -->

<template>
    <div class="ContactSection">
        <div class="title">
            <h1>contatti.</h1>
        </div>
        <div class="description">
            <div class="image">
                <img class="photo" src="data:image/jpeg;base64,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"/>
            </div>
            <div class="links">
                <p>
                    Per contattarmi riguardo offerte di lavoro o opportunità formative qui sotto troverete tutti i miei recapiti:
                </p>
                <br>
                <p class="recapiti">
                    Email: pietro.coin02@gmail.com
                    <br>
                    Cellulare: 373 834 7202
                    <br>
                    LinkedIn: linkedin.com/Pietro Coin
                </p>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
    div {
        color: #14213d;
    }

    .ContactSection {
        margin-left: 1rem;
        margin-top: 2rem;
        padding: 4rem;
    }

    .title{
        margin: 2rem;
        margin-bottom: -3px;
    }
     h1 {
        font-size: 3rem;
        font-weight: bolder;
        color: #fca311;
    }

    .description {
        display: flex;

    }

    .image {
        flex: 1%;
    }
    .photo {
        width: 400px;
        height: auto;
        margin:1rem
    }

    .links{
        flex: 1%;
        padding: 4rem;
        font-size: 1rem;
    }

    .recapiti{
       
        font-weight: bold;
    }
</style>