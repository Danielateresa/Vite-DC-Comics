<script>
export default {
    name: 'BlueSection',
    data() {
        return {

            items: [
                {
                    icon: 'buy-comics-digital-comics.png',
                    text: 'digital comics',
                },
                {
                    icon: 'buy-comics-merchandise.png',
                    text: 'dc merchandise',
                },
                {
                    icon: 'buy-comics-shop-locator.png',
                    text: 'subescription',
                },
                {
                    icon: 'buy-comics-subscriptions.png',
                    text: 'comic shop locator',
                },
                {
                    icon: 'buy-dc-power-visa.svg',
                    text: 'dc power visa',
                }
            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL(`../assets/img/${name}`, import.meta.url).href
        }
    }
}
</script>

<template>
    <div class="blue_bar">
        <div class="container">
            <div class="row">
                <div class="col" v-for="item in items">
                    <div class="buy_logo d-flex text-uppercase">
                        <img :src="getImageUrl(item.icon)" alt="">
                        <span>{{ item.text }}</span>
                    </div>
                </div>
                <!-- <div class="col">
                    <div class="buy_logo d-flex text-uppercase">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="lanterna t-shirt">
                        <span>dc merchandise</span>
                    </div>
                </div>
                <div class="col">
                    <div class="buy_logo d-flex text-uppercase">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="card">
                        <span>subscription</span>
                    </div>
                </div>
                <div class="col">
                    <div class="buy_logo d-flex text-uppercase">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="locator">
                        <span>comic shop location</span>
                    </div>
                </div>
                <div class="col">
                    <div class="buy_logo d-flex text-uppercase">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="power card">
                        <span>dc power visa</span>
                    </div> -->

            </div>
        </div>
    </div>

    <!-- /.blue_bar-->
</template>

<style lang="scss" scoped>

</style>