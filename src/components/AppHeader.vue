<script>
import linkMenu from '../assets/data/linkMenu';

export default {
    name: 'AppHeader',
    data() {
        return {
            linkMenu: linkMenu
        }
    }
}
</script>

<template>
    <header id="app_header" class="p-3">
        <div class="container">
            <div class="row">

                <div class="logo col-5">
                    <img class="img-fluid" src="../assets/img/dc-logo.png" alt="">
                </div>
                <!-- /header left -->

                <nav class="navbar navbar-expand col-7">
                    <ul class="nav navbar-nav">
                        <li v-for="link in linkMenu" class="nav-item">
                            <a class="nav-link" :href="link.src">{{ link.text }}</a>
                        </li>
                    </ul>
                </nav>
                <!-- /header right -->

            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
#app_header {
    height: 120px;

    .logo img {
        height: 80px;
    }

    a {
        color: rgba(70, 70, 73, 1);
        font-weight: 600;
    }

    li:hover a {
        color: rgba(2, 130, 249, 1);
    }
}
</style>