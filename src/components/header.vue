<template>
    <div class="main">
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
    </div>
</template>
<style scoped>
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
    height:40px;
    max-width: 1260px;
    max-height: 40px;
}
</style>