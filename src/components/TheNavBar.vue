<template >
    <div class="navBar">
        <p class="name">John Doe</p>
        <div class="nav-bar">
        <p>Home</p>
        <p>About</p>
        <p>Work</p>
        </div>
        <div class="iconNav">
            <img src="src/components/icons/medium-4 1.svg" alt="img" class="iconNav1">
            <img src="src/components/icons/behance-2 1.svg" alt="img" class="iconNav2">
            <img src="src/components/icons/twitter-6 1.svg" alt="img" class="iconNav3">
        </div>
    </div>
</template>
<script lang="ts">
export default {
    
    
    
}
</script>
<style >
.navBar{
    display: flex;
    justify-content: space-between;

}
.name{
    /* John Doe */


width: 114px;
height: 36px;
left: 97px;
top: 34px;

font-family: 'Poppins';
font-style: normal;
font-weight: 600;
font-size: 24px;
line-height: 36px;
/* identical to box height */

/* Dark Blue */
color: #03045E;
}

.nav-bar{

    display: flex;
justify-content: space-between;

width: 276px;
height: 27px;
left: 582px;
top: 37px;
}
.nav-bar p{
    justify-content: space-between;
    align-items: center;
    padding: 1rem;

    
}
.iconNav1{
position: absolute;
width: 26px;
height: 15.05px;
left: 1201px;
top: 42px;
}
.iconNav2{
position: absolute;
width: 26px;
height: 16.1px;
left: 1256px;
top: 42px;
}
.iconNav3{
position: absolute;
width: 26px;
height: 17.79px;
left: 1311px;
top: 41px;
}

</style>