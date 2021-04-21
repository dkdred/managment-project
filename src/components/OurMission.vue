<template>
    <div class="our-mission--wrapper">
        <img src="@/assets/image_2.png" class="our-mission--img">
        <div class="our-mission--info-block">
            <div class="our-mission--info-wrapper">
                <h5 class="our-mission--upper-title">Надежное качество </h5>
                <h1 class="our-mission--title">Наша миссия</h1>
                <p class="our-mission--text">Наша миссия заключается в распространении качественной продукции от знаменитых брендов в Республике Казахстан. </p>
            </div>
            <div class="our-mission--straight-block">
                <div class="our-mission--straight"></div>
                <div class="our-mission--straight"></div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "OurMission"
    }
</script>

<style scoped>
    .our-mission--wrapper{
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding-top: 60px;
    }
    .our-mission--info-wrapper{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    .our-mission--info-block{
        display: flex;
        width: 467px;
        height: 620px;
        margin-right: 23px;
        flex-direction: column;
        justify-content: space-between;
    }
    .our-mission--upper-title{
        font-size: 17px;
        line-height: 19px;
        color: #D81696;
    }
    .our-mission--title{
        font-family: Georgia;
        font-size: 64px;
        line-height: 73px;
        color: #FFFFFF;
        margin-top: 13px;
    }
    .our-mission--text{
        font-family: Georgia;
        font-size: 17px;
        line-height: 19px;
        color: #FFFFFF;
        margin-top: 44px;
    }
    .our-mission--straight-block{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        width: 380px;
        height: 97px;
    }
    .our-mission--straight{
        width: 380px;
        height: 0;
        border: 1px solid #D81696;
    }
</style>
