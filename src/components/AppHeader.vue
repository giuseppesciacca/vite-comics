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
    <header id="app_header" class="">
        <div class="container">
            <div class="row">

                <div class="logo col-12 col-md-5 col-lg-5 d-flex align-items-center">
                    <img class="img-fluid" src="../assets/img/dc-logo.png" alt="">
                </div>
                <!-- /header left -->

                <nav class="navbar navbar-expand col-12 col-md-7 col-lg-7 p-0">
                    <ul class="nav navbar-nav ">
                        <li v-for="link in linkMenu" class="nav-item d-flex align-items-center">
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
@use '../assets/scss/partials/variables.scss' as *;

#app_header {
    .logo img {
        height: 80px;
    }

    li {
        height: 120px;
    }

    a {
        color: $darkLight;
        font-weight: 600;
    }

    li:hover {
        border-bottom: 5px solid $primary;
        cursor: pointer;
    }

    li:hover a {
        color: $primary;
        margin-bottom: -5px;
    }
}
</style>