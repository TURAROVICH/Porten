<template>
    <div class="main">
        <div class="container">
            <div class="shop">
                 <div class="title">О магазине</div>
                 <div class="text">
                     Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum fugit, dolorum fugiat dolores iure vel consectetur officia pariatur ipsum voluptate maxime ad quas. Hic dolorem enim reiciendis tenetur excepturi! Minus.
                 </div>
            </div>

            <div class="categories-container">
                 <div class="title">Категории</div>
                  <div class="categories">
                         <div class="category">
                             <div>часы</div>
                         </div>

                          <div class="category">
                             <div>браслеты</div>
                         </div>

                          <div class="category">
                             <div>ремни</div>
                         </div>

                          <div class="category">
                             <div>ювелирные изделия</div>
                         </div>

                          <div class="category">
                             <div>запонки</div>
                         </div>
                  </div>
            </div>

            <div class="mailing">
                 <div class="title">РАссылка</div>
                 <div class="text">
                     Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mi semper viverra nunc cursus tortor lectus nunc nulla nibh.
                 </div>
                 <div class="form">
                     <input placeholder="Ваша почта ..." class="input" type="text">
                     <button><p>ПОДПИСАТЬСЯ</p></button>
                 </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.category{
    background: #0f0f0f;
    margin: 3px;
}
.category div{
    padding: 15px 25px;
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 150%;
/* identical to box height, or 21px */


/* light-gray */

color: #D0D0D0;

}
.categories{
    display: flex;
    justify-content: space-around;
    width: 300px;
    flex-wrap: wrap;
}
button p{
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 150%;
/* identical to box height, or 21px */

letter-spacing: 0.05em;

/* white */

color: #FFFFFF;
}
.input{
    background: rgba(255, 255, 255, 0.6);
    width: 210px;
height: 42px;
color: #fff;
border: none;
outline: none;
}
button{
    background: #0f0f0f;
    width: 140px;
    height: 42px;
    outline: none;
    border: 1px solid rgba(255, 255, 255, 0.4);
    cursor: pointer;
}
.form{
    display: flex;
    margin-top: 30px;
    align-items: center;
    justify-content: center;
}
.mailing{
    width: 300px;
}
.text{
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 150%;
color: #FFFFFF;

}
.shop{
    width: 300px;
}
.main{
    display: flex;
    align-items: center;
    justify-content: center;
    background: url("../assets/footerbg.png");
    height: 400px;
    background-size: cover;
    background-position: center;
}
.container{
    width: 1000px;
        display: flex;
    /* align-items: center; */
    justify-content: space-between;
    flex-wrap: wrap;
}
.title{
    font-family: Playfair Display;
font-style: normal;
font-weight: normal;
font-size: 24px;
line-height: 32px;
margin-bottom: 30px;
text-transform: uppercase;
color: #FFFFFF;
}
@media screen and (max-width:920px){
    .container{
        width: 100%;
        align-items: center;
        justify-content: space-around;
    }
    .main{
        height: 600px;
    }
}
</style>