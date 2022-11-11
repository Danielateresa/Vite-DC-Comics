<script>
import Card from './CardItem.vue'; //singola card da fare
import cards from '../data/comics.js';

export default {
    components: {
        Card,
    },
    data() {
        return {
            cards
        }
    },
}
</script>

<template>

    <div class="container cards px-4 pb-4">
        <div class="tag">
            <span>current series</span>
        </div>
        <div class="row px-4 d-flex">

            <Card v-for="card in cards" :image="card.thumb" :title="card.series" />


            <!--  <div class="col-2 mt-5" v-for="card in cards">
                <div class="comic_card">
                    <img :src="card.thumb" alt="">
                    <span>{{ card.series }}</span>
                </div>
            </div> -->
        </div>

        <div class="button_box text-center mt-5">
            <button class="btn load_more">
                load more
            </button>
        </div>
    </div>
    <!-- ./cards -->

</template>