<script>
export default {
    name: 'SiteHeader'
}
</script>

<template>
    <header id="site_header">
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="dc logo">
            </div>
            <nav>
                <ul>
                    <li><a href="">characters</a></li>
                    <li><a href="">comics</a></li>
                    <li><a href="">movies</a></li>
                    <li><a href="">tv</a></li>
                    <li><a href="">games</a></li>
                    <li><a href="">collectibles</a></li>
                    <li><a href="">videos</a></li>
                    <li><a href="">fans</a></li>
                    <li><a href="">news</a></li>
                    <li><a href="">shop</a></li>
                </ul>
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

ul {
    display: flex;

}
</style>