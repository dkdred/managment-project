<template>
    <div class="slider-wrapper">
        <VueSlickCarousel
                :arrows="false"
                :dots="false"
                :autoplay="true"
                :infinite="true"
                :draggable="false"
        >
            <img class="slider-item" src="https://source.unsplash.com/random" />
            <img class="slider-item" src="https://source.unsplash.com/random?q=1" />
            <img class="slider-item" src="https://source.unsplash.com/random?q=2" />

        </VueSlickCarousel>
        <div class="slider--overlay">
            <div class="container">
                <div class="overlay--wrapper">
                    <h5 class="slider--up-title">Лучшая косметика разных брендов </h5>
                    <h1 class="slider--title">
                        Мы на стороне вашей красоты и здоровья
                    </h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import VueSlickCarousel from 'vue-slick-carousel'
    import 'vue-slick-carousel/dist/vue-slick-carousel.css'

    export default {
        name: "HeaderBanner",
        components: { VueSlickCarousel },
    }
</script>

<style scoped>
    .slider-wrapper{
        width: 100%;
        height: 607px;
        position: relative;
    }
    .slider-item{
        width: 100%;
        height: 607px;
    }
    .slider--overlay{
        position: absolute;
        width: 100%;
        height: 607px;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        background: #00000080;
        display: flex;
        flex-direction: column;

    }
    .slider--title{
        height: 164px;
        width: 868px;
        left: 45px;
        top: 208px;
        font-family: Georgia;
        font-size: 72px;
        font-style: normal;
        font-weight: 700;
        line-height: 82px;
        letter-spacing: 0em;
        text-align: left;
        color: white;
        z-index: 999;
        opacity: 1;
    }
    .slider--up-title{
        height: 54px;
        width: 375px;
        left: 45px;
        top: 127px;
        font-family: Georgia;
        font-size: 24px;
        font-style: italic;
        font-weight: 400;
        line-height: 27px;
        letter-spacing: 0em;
        text-align: left;
        color: #D81696;
        margin-bottom: 27px;

    }
    .container {
        margin:0 45px 0 45px;
    }
    .overlay--wrapper{
        height: 607px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: center;
    }
</style>
