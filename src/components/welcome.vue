<template>
    <div id="porten" class="main">
        <div class="container">
            <div class="logo">
                 <div class="border">
                         <img src="@/assets/PORTEN.png" alt="">
                          <div class="line"></div>
                          <div class="city">санкт-петербург</div>
                 </div>
            </div>
            <div class="some-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus dicta 
                et doloribus laudantium. Cum, vitae consequatur provident eos molestiae quasi soluta laborum? 
                Recusandae odit nemo vel libero dolore id beatae.
            </div>
           
        </div>
    </div>
</template>

<style scoped>
.main{
    width: 100%;
    height: 81.8vh;
    background: url("../assets/bg.png") no-repeat;
    box-sizing: border-box;
    background-size: cover;
    background-position:  center;
}
.container{
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
}
.city{
    text-transform: uppercase;
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 28px;
text-align: center;
text-transform: uppercase;

color: #FFFFFF;
}
.border{
    margin-top: 40px;
    border: 4px solid #fff;
    width: 260px;
    height: 260px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
     background: rgba(0,0,0,0.5);
}

.some-text{
    width: 400px;
    text-align: center;
    margin-top: 30px;
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 13px;
line-height: 150%;
/* or 24px */

text-align: center;
text-transform: uppercase;

color: #FFFFFF;
}
</style>