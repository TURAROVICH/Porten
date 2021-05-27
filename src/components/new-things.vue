<template>
    <div class="main">
        <div class="container">
            <div class="container-title">
                <div class="title">
              новые поступления
            </div>
            <div class="line"></div>

            </div>
            <div class="product-container">
                   <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/><Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/><Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
          <Card  title="Louis XVI ATHOS" price="165 000 руб."/>
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
.container-title{
      display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-bottom: 60px;
}
.product-container{
      display: flex;
    align-items: center;
    justify-content: space-evenly;
    flex-wrap: wrap;
}
.main{
    display: flex;
    align-items: center;
    justify-content: center;
    /* height: 100vh; */
}
.container{
    /* height: 100%; */
    width: 900px;
     display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
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
</style>