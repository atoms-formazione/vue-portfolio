<template>
    <div class="container">
        <div class="image">
            <img src="https://static.vecteezy.com/system/resources/previews/014/032/678/original/grey-laptop-computer-with-envelope-cloud-arrow-isolated-sending-receiving-email-marketing-concept-3d-illustration-or-3d-render-png.png">
        </div>
        <div class="infos">
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptate enim accusantium nemo temporibus optio modi perspiciatis quo fugiat labore aut rerum nobis consequuntur maiores quasi dolor, amet eius dolorem voluptates.</p>
            <br>
            <ul>
                <li>email@email.com</li>
                <li>twitter.com/dubdududu</li>
                <li>bubu.com/sasasa</li>
            </ul>

        </div>
    </div>
    </template>

<script setup lang="ts">

</script>

<style scoped>
.container{
    margin-left: 5%;
    margin-right: 5%;
    display: flex;
    background-color: violet;
    justify-content: space-around;
    padding-bottom: 5rem;
    bottom: 0;
}


.image {
 flex: 2;
 text-align: center;
}
.image>img{
    margin-top: 3rem;
    width: 75%;
}
.infos{
flex: 3;
width: 90%;
margin: 3%;
padding: 3%;
margin-bottom:0;
font-size: 1.2rem;
}
</style>