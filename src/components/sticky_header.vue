<template>
    <div class="main flex">
          <div class="flex container ">
              <div class="logo flex">
                   <img src="@/assets/PORTEN.png" alt="">
              </div>

              <div class="headers flex">
                   <div class="flex headers_container">
                          <a href="#porten"><div @click="handle(1)" :class="{active:active}"><p>Porten</p></div></a>
                         <a href="#sezon"> <div @click="handle(2)" :class="{active:active1}"><p>Сезон</p></div></a>
                          <a href="#collections"><div @click="handle(3)" :class="{active:active2}"><p>Коллекция</p></div></a>
                   </div>
                   <div class="support_icons flex">
                       <img src="" alt="">
                       <img src="" alt="">
                   </div>
              </div>
          </div>
    </div>
</template>
<script>
export default {
    data:()=>({
        active:false,
        active1:false,
        active2:false,
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
    }
}
</script>
<style scoped>
a{
    text-decoration: none;
}
.active{
    background:  #1F1F1F;;
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
</style>