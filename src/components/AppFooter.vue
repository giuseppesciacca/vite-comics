<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer id="app_footer">

        <div id="footer_top" class="px-3 text-white">
            <div class="container">
                <div class="row">
                    <div class="col py-4">

                        <div class="row">
                            <div class="col">
                                <ul class="p-0">
                                    <li>
                                        <h4>DC COMICS</h4>
                                    </li>
                                    <li>
                                        <a href="#">Characters</a>
                                    </li>
                                    <li>
                                        <a href="#">Comics</a>
                                    </li>
                                    <li>
                                        <a href="#">Movies</a>
                                    </li>
                                    <li>
                                        <a href="#">TV</a>
                                    </li>
                                    <li>
                                        <a href="#">Games</a>
                                    </li>
                                    <li>
                                        <a href="#">Videos</a>
                                    </li>
                                    <li>
                                        <a href="#">News</a>
                                    </li>
                                </ul>

                                <ul class="p-0">
                                    <li>
                                        <h4>SHOP</h4>
                                    </li>
                                    <li>
                                        <a href="#">Shop DC</a>
                                    </li>
                                    <li>
                                        <a href="#">Shop DC Collectibles</a>
                                    </li>
                                </ul>
                            </div>

                            <div class="col">
                                <ul class="p-0">
                                    <li>
                                        <h4>DC</h4>
                                    </li>
                                    <li>
                                        <a href="#">Terms Of Use</a>
                                    </li>
                                    <li>
                                        <a href="#">Privacy policy (New)</a>
                                    </li>
                                    <li>
                                        <a href="#">Ad Choices</a>
                                    </li>
                                    <li>
                                        <a href="#">Advertising</a>
                                    </li>
                                    <li>
                                        <a href="#">Jobs</a>
                                    </li>
                                    <li>
                                        <a href="#">Subscriptions</a>
                                    </li>
                                    <li>
                                        <a href="#">Talent Workshops</a>
                                    </li>
                                    <li>
                                        <a href="#">CPSC Certificates</a>
                                    </li>
                                    <li>
                                        <a href="#">Ratings</a>
                                    </li>
                                    <li>
                                        <a href="#">Shop Help</a>
                                    </li>
                                    <li>
                                        <a href="#">Contact Us</a>
                                    </li>
                                </ul>
                            </div>

                            <div class="col">
                                <ul class="p-0">
                                    <li>
                                        <h4>SITES</h4>
                                    </li>
                                    <li>
                                        <a href="#">DC</a>
                                    </li>
                                    <li>
                                        <a href="#">MAD Magazine</a>
                                    </li>
                                    <li>
                                        <a href="#">DC Kids</a>
                                    </li>
                                    <li>
                                        <a href="#">DC Universe</a>
                                    </li>
                                    <li>
                                        <a href="#">DC Power Visa</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="col" id="logo_bg_main"></div>
                </div>
            </div>
        </div>
        <!-- /#footer_top -->

        <div id="footer_bottom" class="text-white px-3">
            <div class="container">
                <div class="row">
                    <div class="col d-flex align-items-center">
                        <button class="my_btn btn">SIGN-UP NOW!</button>
                    </div>

                    <div class="col d-flex align-items-center justify-content-end">
                        <a class="pe-3 m-0 fw-bold text-decoration-none" href="">FOLLOW US</a>

                        <a href="#"><img class="pe-3" src="../assets/img/footer-facebook.png" alt=""></a>

                        <a href="#"><img class="pe-3" src="../assets/img/footer-twitter.png" alt=""></a>

                        <a href="#"><img class="pe-3" src="../assets/img/footer-youtube.png" alt=""></a>

                        <a href="#"><img class="pe-3" src="../assets/img/footer-pinterest.png" alt=""></a>

                        <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
                    </div>
                </div>
            </div>
        </div>
        <!-- /#footer_bottom -->
    </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

#app_footer {
    #footer_top {
        min-height: 370px;
        background-image: url(../assets/img/footer-bg.jpg);

        #logo_bg_main {
            background-image: url(../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-position: center;
        }

        ul {
            list-style: none;

            h4 {
                font-weight: bold;
            }

            a {
                text-decoration: none;
                color: $linkFooter;
            }

            a:hover {
                color: $lighter;
            }
        }
    }

    #footer_bottom {
        background-color: $secondary;
        min-height: 110px;

        .col {
            height: 110px;

            .my_btn {
                border: 2px solid $primary;
                border-radius: 0;
                color: white;
                padding: 0.5rem;
            }

            p {
                color: $primary;
            }
        }
    }
}
</style>