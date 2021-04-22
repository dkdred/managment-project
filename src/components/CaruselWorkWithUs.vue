<template>
    <div>
        <marquee-text :repeat="10" :reverse="true">
            <div class="carusel--wrapper">
                <p  class="carusel-text">Работай с нами</p>
                <img class="carusel--img" src="@/assets/Union.png" alt="">
            </div>
        </marquee-text>
        <marquee-text :repeat="10">
            <div class="carusel--wrapper">
                <p  class="carusel-text">Работай с нами</p>
                <img class="carusel--img rotate" src="@/assets/Union.png" alt="">
            </div>
        </marquee-text>
    </div>

</template>

<script>
    import MarqueeText from 'vue-marquee-text-component'

    export default {
        name: "CaruselWorkWithUs",

        components: {
            MarqueeText
        }
    }
</script>

<style scoped>
    .carusel--wrapper{
        width: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
    }
    .carusel-text{
        font-family: Roboto;
        font-weight: 500;
        font-size: 80px;
        line-height: 94px;
        color: #FFFFFF;
    }
    .carusel--img{
        margin:0 10px 0 10px;
    }
    .rotate{
        transform: rotateY(180deg) ;

    }
</style>
