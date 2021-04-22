<template>
    <div class="products">
        <our-products></our-products>
        <delivery-info></delivery-info>
    </div>
</template>

<script>
    import DeliveryInfo from "../components/DeliveryInfo";
    import OurProducts from "../components/OurProducts";

    export default {
        name: "Products",
        components: {
            DeliveryInfo,
            OurProducts
        }
    }
</script>

<style scoped>
    .products{
        background: #19181D;
    }
</style>
