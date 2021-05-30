<template>
    <div class="main">
        <div class="container">
            <div class="title-container">
                 <div class="title">наши бренды</div>
                 <div class="line"></div>
            </div>
            <div class="brends">
                 <div class="brend">
                     <img src="../assets/brends.png" alt="">
                 </div>
                  <div class="brend">
                     <img src="../assets/brends.png" alt="">
                 </div>
                  <div class="brend">
                     <img src="../assets/brends.png" alt="">
                 </div>
               
            </div>
        </div>
    </div>
</template>

<style scoped>
.brends{
     display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
}
.title-container{
     display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.main{
    background: #0F0F0F;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 300px;
}
.container{
    width: 900px;

}
.title{
    font-family: Playfair Display;
font-style: normal;
font-weight: bold;
font-size: 36px;
line-height: 48px;
/* identical to box height */

text-align: center;
text-transform: uppercase;

/* white */

color: #FFFFFF;

}
@media screen and (max-width:520px) {
    .main{
        height: 400px;
    }
}
</style>