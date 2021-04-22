<template>
    <div class="container">
        <h1 class="title">Наши товары</h1>
        <div class="products-wrapper">
            <div class="products-item">
                <img src="@/assets/pr_1.png" alt="" class="products--img">
                <p class="products--name">Косметика</p>
                <p class="products--cost">21000тг.</p>
                <a class="products--btn">Купить</a>
            </div>
            <div class="products-item">
                <img src="@/assets/pr_2.png" alt="" class="products--img">
                <p class="products--name">ELEMIS </p>
                <p class="products--cost">34000тг.</p>
                <a class="products--btn">Купить</a>
            </div>
            <div class="products-item">
                <img src="@/assets/pr_3.png" alt="" class="products--img">
                <p class="products--name">Elemis</p>
                <p class="products--cost">18000тг.</p>
                <a class="products--btn">Купить</a>
            </div>
            <div class="products-item">
                <img src="@/assets/pr_4.png" alt="" class="products--img">
                <p class="products--name">ordinary</p>
                <p class="products--cost">4900тг.</p>
                <a class="products--btn">Купить</a>
            </div>
            <div class="products-item">
                <img src="@/assets/pr_5.png" alt="" class="products--img">
                <p class="products--name">ordinary blue</p>
                <p class="products--cost">8900тг.</p>
                <a class="products--btn">Купить</a>
            </div>
            <div class="products-item">
                <img src="@/assets/pr_6.png" alt="" class="products--img">
                <p class="products--name">Парфюм</p>
                <p class="products--cost">11000тг.</p>
                <a class="products--btn">Купить</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "OurProducts"
    }
</script>

<style scoped>
    .container{
        padding: 30px 45px 50px 45px ;
    }
    .title{
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
    .products-wrapper{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        justify-content: space-between;
        margin-top: 30px;
    }
    .products-item{
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
    }
    .products--img{
        width: 350px;
        height: 350px;
    }
    .products--name{
        font-family: Georgia;
        font-weight: bold;
        font-size: 18px;
        line-height: 20px;
        color: #ffffff;
        margin-top: 15px;
    }
    .products--cost{
        font-family: Georgia;
        font-weight: bold;
        font-size: 18px;
        line-height: 20px;
        color: #ffffff;
        margin-top: 10px;
    }
    .products--btn{
        background: #D81696;
        padding: 10px 26px 10px 26px;
        border-radius: 50px;
        font-family: Georgia;
        font-size: 18px;
        line-height: 20px;
        font-weight: bold;
        margin-top: 10px;
        margin-bottom: 20px;
    }
</style>
