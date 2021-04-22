<template>
    <div class="container">
        <div class="contacts--title-block">
            <h1 class="contacts--title">Наши контакты </h1>
            <img src="@/assets/arrow_up.png" alt="" class="contacts--img">
        </div>
        <div class="contacts--info-block">
            <div class="contacts--mainsion-block">
                <span class="contacts--number">Сот. номер:  <a href="">+7 707 77 77 777</a></span>
            </div>
            <div class="contacts--mainsion-block">
                <a class="contacts--socail-link" href="">Instagram</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>
    .container{
        padding: 0 45px 0 45px;
        background: #19181d;
    }
    .contacts--title-block{
        width: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: flex-start;
    }
    .contacts--title{
        font-family: Roboto;
        font-weight: 500;
        font-size: 120px;
        line-height: 141px;
        color: #FFFFFF;
    }
    .contacts--img{
        margin-left: 48px;
    }
    .contacts--info-block{
        margin-top: 66px;
        padding-bottom: 38px;
        width: 100%;
        display: flex;
        flex-direction: row;

    }
    .contacts--mainsion-block{
        width: 50%;

    }
    .contacts--number{
        font-family: Roboto;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
        color: #FFFFFF;
    }
    .contacts--number>a{
        color: #D81696;
    }
    .contacts--socail-link{
        font-family: Roboto;
        font-weight: 500;
        font-size: 18px;
        line-height: 21px;
        text-decoration-line: underline;
        color: #FFFFFF;
    }
</style>
