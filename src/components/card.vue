<template>
    <div class="main">
         <div class="center image">
             <div class="container">
                    <img src="../assets/watch.png" alt="jjj">
             </div>
         </div>
         <div class="content">
             <div class="title">{{title}}</div>
             <div class="price">{{price}} </div>
         </div>
    </div>
</template>

<script>
export default {
    props:{
        title:{
            type: String,
            required:true
        },
        price:{
            type: String,
            required:true
        }

    }
}
</script>

<style scoped>
.center{
    display: flex;
    justify-content: center;
    align-items: center;
}
.main{
        width: 230px;
  height: 330px;
  display: flex;
  flex-direction: column;
  margin-bottom: 30px;
}
.image{
    width: 230px;
height: 295px;
background: #191B1C;

}
.content{
        width: 260px;
        height: 35px;
        font-family: Playfair Display;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 24px;
    color: #D0D0D0;
    margin-top: 8px;
    text-align-last: center;
}
.container{
    width: 215px;
   height: 214px;
}

</style>