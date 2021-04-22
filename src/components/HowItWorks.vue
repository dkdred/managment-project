<template>
    <div class="container">
        <h1 class="how-it-works--title">Как мы работаем? </h1>
        <div class="how-it-works--items-block">
            <div class="how-it-works--items">
                <h3 class="how-it-works--items-number">01</h3>
                <p class="how-it-works--items-text">Мы закупаем товар у оригинальных производителей.</p>
            </div>
            <div class="how-it-works--items">
                <h3 class="how-it-works--items-number">02</h3>
                <p class="how-it-works--items-text">Выставляем данный товар с нашей гарантией на сайте.</p>
            </div>
            <div class="how-it-works--items">
                <h3 class="how-it-works--items-number">03</h3>
                <p class="how-it-works--items-text">Доставляем путем курьера, либо по почте.</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "HowItWorks"
    }
</script>

<style scoped>
    .container{
        padding: 87px 30px 0 30px;

    }
    .how-it-works--title{
        font-family: Roboto;
        font-weight: 500;
        font-size: 48px;
        line-height: 56px;
        color: #FFFFFF;
    }
    .how-it-works--items-block{
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-top: 56px;
    }
    .how-it-works--items{
        background: rgba(196, 196, 196, 0.01);
        width: 25%;
        height: 497px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        transition: 0.3s;
        position: relative;
    }
    .how-it-works--items:before{
        content: '';
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        background-image: url("../assets/back_card.png");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        transition: 0.3s;
        opacity:  0;
    }
    .how-it-works--items:hover:before{
        opacity: 1;
    }
    .how-it-works--items-number{
        font-family: Roboto;
        font-weight: 500;
        font-size: 120px;
        line-height: 141px;
        color: #D81696;
        z-index: 999;

    }
    .how-it-works--items-text{
        font-family: Roboto;
        font-weight: normal;
        font-size: 17px;
        line-height: 20px;
        color: #FFFFFF;
        z-index: 999;
        width: 70%;
    }
</style>
