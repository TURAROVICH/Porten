<template>
    <div id="collections" class="main">
        <div class="bg"></div>
        <div class="collection">
            <div class="container">
            <div class="title">коллекция 2018</div>
            <div style="margin-top:30px;" class="line"></div>
            <div class="text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non rutrum ornare ut mattis habitant dui arcu. Sagittis amet nunc ut neque quis nibh arcu. Vivamus vestibulum nisi et venenatis sed scelerisque magna consectetur. Amet convallis quis gravida facilisis vulputate. Faucibus facilisi habitasse ipsum interdum dictum aliquet. Velit quis ullamcorper pulvinar nulla malesuada integer. Aenean praesent viverra nulla nullam natoque volutpat curabitur auctor. Viverra viverra ullamcorper scelerisque risus dignissim egestas. Id aliquam a aliquam egestas leo orci pharetra sed diam. 
            </div>
            <div class="btn-catalog"><p>посмотреть коллекцию</p></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.text{
    margin-top: 50px;
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 150%;
/* or 21px */

text-align: center;

/* white */

color: #FFFFFF;
}
.bg{
    background: url("../assets/2018-col.png") no-repeat;
    width: 50vw;
    height: 100vh;
    background-position: center;
    background-size: cover;

}
.collection{
    width: 50vw;
    height: 100vh;
    color: aliceblue;
     display: flex;
     align-items: center;
     justify-content: center;
}
.container{
    width: 350px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: -100px;
}
.btn-catalog{
    margin-top: 30px;
    width: 311px;
    height: 47px;
    border: 1px solid #fff;
    background: rgba(0,0,0,0.6);
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 23px;
text-align: center;
letter-spacing: 0.1em;
text-transform: uppercase;
color: #FFFFFF;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;  
  cursor: pointer;
}
.title  {
    font-family: Playfair Display;
font-style: normal;
font-weight: normal;
font-size: 36px;
line-height: 48px;
text-align: center;
text-transform: uppercase;

}
.main{
    display: flex;
}
@media screen and (max-width:637px) {
    .main{
        flex-direction: column-reverse;
        justify-content: center;
        align-items: center;
        /* background: #000; */
        
    }
    .bg{
        width: 100vw;
    }
}
</style>