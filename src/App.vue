<script >
import SiteHeader from './components/SiteHeader.vue';
import SiteMain from './components/SiteMain.vue';
import BlueSection from './components/BlueSection.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    BlueSection,
    SiteFooter

  }
}

</script>

<template>

  <SiteHeader />

  <SiteMain />

  <BlueSection />

  <SiteFooter />

</template>

<style >

</style>
