<script>
export default {
    name: 'Card',
    props: {
        image: String,
        title: String,
    },
}
</script>


<template>
    <div class="col-2 mt-5">
        <div class="comic_card">
            <img :src="image" alt="">
            <span>{{ title }}</span>
        </div>
    </div>
    <!-- singola card -->

</template>

<style>

</style>