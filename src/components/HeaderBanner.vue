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
    }
    .slider-item{
        width: 100%;
        height: 607px;
    }
</style>
