<template>
    <div class="container">
        <div class="points--wrapper">
            <div class="points--item">
                <div class="points--number-block">
                    <h3 class="points--number">01</h3>
                </div>
                <div class="points--info-block">
                    <h2 class="points-title">Инновационные технологии</h2>
                    <p class="points--text">Мы закупаем товар у оригинальных производителей.</p>
                </div>
            </div>
            <div class="points--item">
                <div class="points--number-block">
                    <h3 class="points--number">02</h3>
                </div>
                <div class="points--info-block">
                    <h2 class="points-title">Професиональная команда</h2>
                    <p class="points--text">В нашей команде отобраны только самые квалифицированные специалисты.</p>
                </div>
            </div>
            <div class="points--item">
                <div class="points--number-block">
                    <h3 class="points--number">03</h3>
                </div>
                <div class="points--info-block">
                    <h2 class="points-title">Карьерный рост</h2>
                    <p class="points--text">Наша компания активно развивается и появляется огромное количество возможностей и рабочих мест.</p>
                </div>
            </div>
            <div class="points--item">
                <div class="points--number-block">
                    <h3 class="points--number">04</h3>
                </div>
                <div class="points--info-block">
                    <h2 class="points-title">Полная поддержка проекта</h2>
                    <p class="points--text">Мы не останавливаемся на достигнутом, мы вводим инновации и поддерживаем проект.</p>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: "Points"
    }
</script>

<style scoped>
    .container{
        padding: 80px 45px 0 45px;

    }
    .points--wrapper{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        align-items: flex-start;
        justify-content: space-between;
    }
    .points--item{
        width: 40%;
        display: flex;
        flex-direction: row;
        margin-bottom: 130px;

    }
    .points--number-block{
        display: flex;
        align-items: flex-start;
        justify-content: flex-start;
    }
    .points--number{
        font-family: Inter;
        font-weight: 500;
        font-size: 130px;
        line-height: 157px;
        color: #303030;
    }
    .points--info-block{
        margin-left: 50px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: flex-start;
    }
    .points-title{
        font-family: Inter;
        font-weight: 500;
        font-size: 36px;
        line-height: 44px;
        color: #D81696;
    }
    .points--text{
        margin-top: 55px;
        font-family: Roboto;
        font-weight: normal;
        font-size: 17px;
        line-height: 20px;
        color: #EAEAEA;
    }
</style>
