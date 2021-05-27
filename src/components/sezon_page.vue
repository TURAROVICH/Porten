<template>
    <div id="sezon" class="main">
         <div class="sezon">
               <div class="title-container">
                    <h4 class="title">СЕЗОН 2020/21</h4>
                    <div class="line"></div>
               </div>
        <div class="cards">
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
        </div>
         </div>

         <div class="collection">
            <div class="collection-container">
                <div class="title">
                  Новая коллекция
                </div>
                <div class="line"></div>

                <div class="btn-catalog"><p>Каталог</p></div>
            </div>
         </div>
    </div>
</template>

<script>
import Card from './card'
export default {
    components:{
        Card
    } 
}
</script>

<style scoped>
.btn-catalog{
    width: 138px;
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

/* white */

color: #FFFFFF;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;  
  margin-top: 30px;
  cursor: pointer;
}
.collection-container{
     display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;  
}
.cards{
    margin-top: 40px;
    flex-wrap: nowrap;
    display: flex;
    justify-content: space-around;
}
.main   {
    height: 730px;
    display: flex;
}
.sezon  {
    width: 60vw;
    background: #000;
    height: 100vh;
}
.collection  {
    width: 40vw;
    background: url("../assets/collection.png") no-repeat;
    height: 100vh;
     display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.title-container{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-top:40px ;
}
.title{
    font-family: Playfair Display;
font-style: normal;
font-weight: bold;
font-size: 36px;
line-height: 48px;
text-align: center;
text-transform: uppercase;

/* white */

color: #FFFFFF;
}
</style>