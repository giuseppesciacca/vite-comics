<script>
import dataCards from '../assets/data/dc-comics.json'
import CardImg from './CardImg.vue';
import BannerMain from './BannerMain.vue';

export default {
    name: "AppMain",
    data() {
        return {
            dataCards: dataCards,
        }
    },
    components: {
        CardImg,
        BannerMain
    }
}
</script>

<template>
    <main id="app_main" class="text-white">

        <div class="jumbotron mb-4"></div>

        <div class="container px-3 py-5 position-relative">
            <div id="current_series" class="position-absolute bg-primary p-3">
                <h2 class="m-0">CURRENT SERIES</h2>
            </div>

            <div class="row">

                <div class="col-2" v-for="card in dataCards">
                    <CardImg :thumb="card.thumb" :series="card.series"></CardImg>
                </div>

                <div class="d-flex justify-content-center">
                    <button class="btn btn-primary rounded-0 d-inline">LOAD MORE</button>
                </div>

            </div>
        </div>
        <!-- /cards -->

        <BannerMain></BannerMain>
        <!-- /.banner_main -->

    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: rgba(28, 28, 28, 1);
}

#current_series {
    top: -60px;
    left: 0;
}

.jumbotron {
    background-image: url(../assets/img/jumbotron.jpg);
    height: 400px;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>