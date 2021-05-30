<template>
    <div class="main flex">
          <div class="flex container ">
              <div @click="width < 500 ? check = true : check=false" class="logo flex">
                   <img src="@/assets/PORTEN.png" alt="">
              </div>

              <div class="headers flex">
                   <div class="flex headers_container">
                          <a href="#porten"><div @click="handle(1)" :class="{active:active}"><p>Porten</p></div></a>
                         <a href="#sezon"> <div @click="handle(2)" :class="{active:active1}"><p>Сезон</p></div></a>
                          <a href="#collections"><div @click="handle(3)" :class="{active:active2}"><p>Коллекция</p></div></a>
                   </div>
              </div>
          </div>

    <div  id="modal" v-if="check">
         <div class="container">

                <div class="support-text">
                    <ul>
                        <li> <img src="@/assets/Vector.svg" alt=""> 8(812)123-45-67</li>
                        <li> Работаем 7 дней в неделю </li>
                        <li> 9:00—18:00</li>
                    </ul>
                </div>

                <div class="check-auth">
                     <img src="@/assets/logout-icon.png" alt="">
                     <p>Войти / Регистрация</p>
                </div>
         </div>

                   <div class="flex headers_container">
                          <a href="#porten"><div @click="handle(1)" :class="{active:active}"><p>Porten</p></div></a>
                         <a href="#sezon"> <div @click="handle(2)" :class="{active:active1}"><p>Сезон</p></div></a>
                          <a href="#collections"><div @click="handle(3)" :class="{active:active2}"><p>Коллекция</p></div></a>
                   </div>

                    <div @click="check=false" class="close-modal">Close</div>

              </div>

    </div>
</template>
<script>
export default {
    data:()=>({
        active:false,
        active1:false,
        active2:false,
        width:null,
        check:false
    }),
    methods:{
        handle(n){
          if(n==1){
              this.active = true
                this.active1=false
                 this.active2=false
          }else if(n==2){
              this.active1 = true
              this.active=false
                 this.active2=false
          }else if(n==3){
              this.active2 = true
                 this.active=false
                 this.active1=false   
          }
        }
    },
    mounted(){
        this.width = document.body.clientWidth
        
    },

    
}
</script>
<style scoped>
.close-modal{
    font-size: 20px;
    font-weight: 900;
    position: fixed;
    /* left: 50%; */
    z-index: 1001;
   color:  #C0392B;
   margin-top: 400px;
}
#modal{
    position: fixed;
    width: 80vw;
    height: 90vh;
    z-index: 1000;
    top:3vh;
    background: rgba(0,0,0,0.9);
    flex-direction: column;
    display: flex;
    justify-content: center;
    align-items: center;
    border:3px solid #fff;
}






*{
    font-style: normal;
font-weight: normal;
font-size: 12px;
line-height: 16px;
color: #969696;
}
.check-auth{
    display: flex;
    align-items: center;
    justify-content: center;
}
.check-auth img{
    margin-right: 10px;
}
.support-text ul {
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.support-text ul li:not(:nth-child(1)){
    margin-left: 10px;
}
li{
    list-style: none;
}
.main{
    max-width: 1920px;
    max-height: 80px;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content:center;
    align-items: center;
        background: #000000;
}
.container{
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 1260px;
    height:80px;
    max-width: 1260px;
    max-height: 40px;
    flex-wrap: wrap;
    /* margin-top: -10px; */
}















a{
    text-decoration: none;
}
.active{
    background:  #1F1F1F;
    width: 300px;

}
.headers_container div{
    cursor: pointer;
    display: flex;
    font-family: PT Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 18px;
text-transform: uppercase;
color: #FFFFFF;
width: 130px;
height: 80px;
text-align: center;
justify-content: space-around;
align-items: center;
}

.flex{
    display: flex;
    justify-content: center;
    align-items: center;
}
.main{
    max-width: 1920px;
    max-height: 80px;
    background:  #0F0F0F;
    width: 100%;
}
.container{
    width:100%;
    height: 80px;
    justify-content: space-around;
}
@media screen and (max-width: 500px){
    .container{

    }
    .headers{
        display: none;
        overflow: hidden;
    }
    .headers_container{
        flex-direction: column;
    }
}
</style>