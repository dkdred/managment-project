<template>
    <div class="container">
        <h1 class="title">Информация о доставке</h1>
        <p class="info-text">Мы dga находимся в городе Алматы. Вы можете самостоятельно забрать покупку из точки самовывоза или заказать доставку курьером по Алматы и Алматинской области. Также доступна доставка почтой по всему Казахстану</p>
    </div>
</template>

<script>
    export default {
        name: "DeliveryInfo"
    }
</script>

<style scoped>
    .container{
        padding: 30px 100px 50px 100px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .title{
        height: 110px;
        width: 868px;
        font-family: Georgia;
        font-size: 52px;
        font-style: normal;
        font-weight: 700;
        line-height: 82px;
        color: white;
        z-index: 999;
        opacity: 1;
        text-align: center;
    }
    .info-text{
        font-size: 32px;
        font-style: normal;
        font-weight: 700;
        line-height: 52px;
        color: white;
        z-index: 999;
        opacity: 1;
        text-align: center;
    }
</style>
