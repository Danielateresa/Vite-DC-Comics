<script>
export default {
    name: 'SiteHeader',
    data() {
        return {
            activeLink: 0,
            menu: [
                {
                    text: 'characters',
                    href: '#'
                },
                {
                    text: 'comics',
                    href: '#'
                },
                {
                    text: 'movies',
                    href: '#'
                },
                {
                    text: 'tv',
                    href: '#'
                },
                {
                    text: 'games',
                    href: '#'
                },
                {
                    text: 'collectibles',
                    href: '#'
                },
                {
                    text: 'videos',
                    href: '#'
                },
                {
                    text: 'fans',
                    href: '#'
                },
                {
                    text: 'new',
                    href: '#'
                },
                {
                    text: 'shop',
                    href: '#'
                }
            ]
        }
    },

}
</script>

<template>
    <header id="site_header">
        <div class="container d-flex align-items-center justify-content-between center text-uppercase">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="dc logo">
            </div>
            <nav class="navbar py-0">
                <div class="link_box ms-4" v-for="item in menu">
                    <a href="item.href">{{
                            item.text
                    }}</a>
                </div>

            </nav>
        </div>

    </header>
    <!-- /#site_header -->
</template>

<style lang="scss" scoped>

</style>