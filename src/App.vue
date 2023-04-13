<script>
export default {

}
</script>

<template>
  <header id="app_header" class="p-3">
    <div class="container">
      <div class="row">

        <div class="logo col-5">
          <img class="img-fluid" src="./assets/img/dc-logo.png" alt="">
        </div>

        <nav class="navbar navbar-expand col-7">
          <ul class="nav navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">CHARACTERS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">COMICS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">MOVIES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">TV</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">GAMES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">COLLECTIBLES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">VIDEOS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">FANS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NEWS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SHOP</a>
            </li>
          </ul>
        </nav>

      </div>
    </div>
  </header>
  <!-- /#app_header -->



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
  <!-- /#app_main -->


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

    <div id="footer_bottom" class="text-white">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nihil laudantium ad perferendis
      quisquam ratione, ipsa a nulla consequatur, magnam doloremque sit nesciunt voluptate architecto error excepturi
      distinctio, maiores sapiente fugit.
    </div>
    <!-- /#footer_bottom -->
  </footer>
  <!-- /#app_footer -->
</template>


<style lang="scss" scoped>
#app_header {
  height: 120px;

  .logo img {
    height: 80px;
  }

  a {
    color: black;
  }
}

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

#app_footer {
  #footer_top {
    height: 370px;
    background-image: url(./assets/img/footer-bg.jpg);

    #logo_bg_main {
      background-image: url(./assets/img/dc-logo-bg.png);
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
        color: grey;
      }
    }

  }

  #footer_bottom {
    background-color: rgba(48, 48, 48, 1);
    height: 110px;
  }
}
</style>