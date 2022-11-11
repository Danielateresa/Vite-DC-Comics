<script>
import BlueSection from './BlueSection.vue';
import CardList from './CardList.vue';

export default {
    name: 'SiteMain',
    components: {
        BlueSection,
        CardList
    },

}
</script>

<template>
    <main id="site_main">
        <div class="comics_jumbotron">

        </div>
        <!-- .comics_jumbotron -->

        <CardList />

        <BlueSection />
    </main>
    <!-- /#site_main -->

</template>

<style lang="scss" scoped>

</style>

