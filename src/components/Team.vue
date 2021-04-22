<template>
    <div class="container">
         <h1 class="title">Наша команда </h1>
        <div class="team-card--wrapper">
            <div class="team-card--row">
                <div class="team-card--item">
                    <img src="@/assets/rimma.png" alt="" class="team-card--img">
                    <h3 class="team-card--position">Social Media Marketing</h3>
                    <p class="team-card--name">Тайшибаева Римма</p>
                </div>
                <div class="team-card--item">
                    <img src="@/assets/os.png" alt="" class="team-card--img">
                    <h3 class="team-card--position">Продукт Project Manager, FrontEnd</h3>
                    <p class="team-card--name">Тамабаев Осмон</p>
                </div>
                <div class="team-card--item">
                    <img src="@/assets/misha.png" alt="" class="team-card--img">
                    <h3 class="team-card--position">Backend Java разработчик</h3>
                    <p class="team-card--name">Сарапулов Михаил </p>
                </div>
                <div class="team-card--item">
                    <img src="@/assets/darkhan.png" alt="" class="team-card--img">
                    <h3 class="team-card--position">Дизайнер</h3>
                    <p class="team-card--name">Нашенов Дархан</p>
                </div>
                <div class="team-card--item">
                    <img src="@/assets/andrey.png" alt="" class="team-card--img">
                    <h3 class="team-card--position">«Менеджер по РАБОТЕ с клиентами»</h3>
                    <p class="team-card--name">Тырбах Андрей </p>
                </div>
                <div class="team-card--item">
                    <img src="@/assets/koliya.png" alt="" class="team-card--img">
                    <h3 class="team-card--position">Контент-менеджер</h3>
                    <p class="team-card--name">Ким Николай</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Team"
    }
</script>

<style scoped>
    .container{
        padding: 87px 30px 0 30px;
    }
    .title{
        font-family: Roboto;
        font-weight: 500;
        font-size: 72px;
        line-height: 84px;
        color: #FFFFFF;
    }
    .team-card--wrapper{
        width: 100%;
        display: flex;
        flex-direction: column;
        margin-top: 90px;
    }
    .team-card--row{
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        flex-wrap: wrap;
        margin: 0 -30px 0 -30px;
    }

    .team-card--item{
        width: 255px;
        display: flex;
        flex-direction: column;
        padding: 0 20px 0 20px;
        margin-bottom: 50px;

    }
    .team-card--position{
        font-family: Inter;
        font-weight: 800;
        font-size: 17px;
        line-height: 21px;
        color: #D81696;
        margin-top: 6px;
    }
    .team-card--name{
        font-family: Inter;
        font-weight: 500;
        font-size: 17px;
        line-height: 21px;
        color: #FFFFFF;
        margin-top: 8px;
    }
</style>
