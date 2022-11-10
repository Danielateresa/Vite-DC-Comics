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
    }
}
</script>

<template>
    <header id="site_header">
        <div class="container py-3 d-flex align-items-center justify-content-between center text-uppercase">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="dc logo">
            </div>
            <nav class="navbar">
                <a class="me-4" href="item.href" v-for="item in menu">{{
                        item.text
                }}</a>

            </nav>
        </div>

    </header>
    <!-- /#site_header -->
</template>

<style lang="scss" scoped>

</style>