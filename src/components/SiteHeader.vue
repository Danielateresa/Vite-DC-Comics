<script>
export default {
    name: 'SiteHeader',
    data() {
        return {
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
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="dc logo">
            </div>
            <nav>
                <a href="item.href" v-for="item in menu">{{ item.text }}</a>

            </nav>
        </div>

    </header>
    <!-- /#site_header -->
</template>

<style scoped>
.container {
    display: flex;
    align-items: center;
}

.logo {
    width: 80px;
    aspect-ratio: 1/1;
}

nav {
    text-transform: uppercase;
}
</style>