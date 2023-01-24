<template >
    <div class="description">
        <p class="greetting">Hello, I’m John, </p>
        <h3 class="profession">Product Designer</h3>
        <p class="local">based in Netherland.</p>
        <button>Resume</button>
    </div>
</template>
<script lang="ts">
export default {
    
}
</script>
<style >
    .profession{
    width: 616px;
height: 232px;
left: 97px;
top: 329px;

font-family: 'Poppins';
font-style: normal;
font-weight: 800;
font-size: 100px;
line-height: 116px;
/* or 116% */
display: flex;
align-items: flex-end;

/* Dark Blue */
color: #03045E;
    }
   .description p{
        
width: 211px;
height: 42px;
left: 97px;
top: 288px;

font-family: 'Poppins';
font-style: normal;
font-weight: 500;
font-size: 28px;
line-height: 42px;
/* identical to box height */

/* Dark Blue */
color: #03045E;
    }
    button{
        position: absolute;
width: 164px;
height: 68px;
left: 97px;
top: 650px;
background-color: #FBF8CC;
    }
    .local{
        position: absolute;
width: 294px;
height: 42px;
left: 97px;
top: 571px;

font-family: 'Poppins';
font-style: normal;
font-weight: 500;
font-size: 28px;
line-height: 42px;
/* identical to box height */

/* Dark Blue */
color: #03045E;

    }
    .greetting{
        position: absolute;
width: 211px;
height: 42px;
left: 97px;
top: 288px;

font-family: 'Poppins';
font-style: normal;
font-weight: 500;
font-size: 28px;
line-height: 42px;
/* identical to box height */

/* Dark Blue */
color: #03045E;
    }
</style>