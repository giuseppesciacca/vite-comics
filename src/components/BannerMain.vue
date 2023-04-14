<script>
export default {
    name: 'BannerMain',
    data() {
        return {
            banner: [
                {
                    text: 'DIGITAL COMICS',
                    src: 'buy-comics-digital-comics.png'
                },
                {
                    text: 'DC MERCHANDISE',
                    src: 'buy-comics-merchandise.png'
                },
                {
                    text: 'SUBSCRIPTION',
                    src: 'buy-comics-subscriptions.png'
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    src: 'buy-comics-shop-locator.png'
                },
                {
                    text: 'DC POWER VISA',
                    src: 'buy-dc-power-visa.svg'
                },
            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL(`../assets/img/${name}`, import.meta.url).href
        }
    },
}
</script>
        
<template>
    <div class="banner_main d-flex align-items-center">
        <div class="container">
            <div class="row text-white align-items-center px-5">

                <div v-for="item in banner" class="col d-flex align-items-center">
                    <img class="img-fluid" :src="getImageUrl(item.src)" alt="">
                    <p class="ps-3 m-0">{{ item.text }} </p>
                </div>
                <!-- /.cols -->

            </div>
            <!-- /.row -->
        </div>
        <!-- /.container -->
    </div>
    <!-- /.banner_main -->
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.banner_main {
    background-color: $primary;
    height: 150px;

    img {
        height: 60px;
    }

    div:last-child>img {
        width: 55px;
    }
}
</style>