<script>
export default {
    name: 'AppMain',
}
</script>

<template>
    <main id="app_main" class=" debug">

        <div class="container px-3 py-5">
            <div>Content goes here</div>
        </div>

        <div class="nav_main d-flex align-items-center">
            <div class="container">
                <div class="row text-white align-items-center px-5">

                    <div class="col d-flex align-items-center">
                        <img class="img-fluid" src="./assets/img/buy-comics-digital-comics.png" alt="">
                        <p class="ps-3 m-0">DIGITAL COMICS</p>
                    </div>
                    <div class="col d-flex align-items-center">
                        <img class="img-fluid" src="./assets/img/buy-comics-merchandise.png" alt="">
                        <p class="ps-3 m-0">DC MERCHANDISE</p>
                    </div>
                    <div class="col d-flex align-items-center">
                        <img class="img-fluid" src="./assets/img/buy-comics-subscriptions.png" alt="">
                        <p class="ps-3 m-0">SUBSCRIPTION</p>
                    </div>
                    <div class="col d-flex align-items-center">
                        <img class="img-fluid" src="./assets/img/buy-comics-shop-locator.png" alt="">
                        <p class="ps-3 m-0">COMIC SHOP LOCATOR</p>
                    </div>
                    <div class="col d-flex align-items-center">
                        <img class="img-fluid" width="55" src="./assets/img/buy-dc-power-visa.svg" alt="">
                        <p class="ps-3 m-0">DC POWER VISA</p>
                    </div>

                </div>
                <!-- /.row -->
            </div>
            <!-- /.container -->
        </div>
        <!-- /.nav_main -->
    </main>
</template>

<style lang="scss" scoped>
main.debug {
    background-color: rgba(28, 28, 28, 1);
    color: white;
}

.nav_main {
    background-color: rgba(2, 130, 249, 1);
    height: 150px;

    img {
        height: 60px;
    }
}
</style>