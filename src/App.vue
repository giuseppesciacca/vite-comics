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
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa ex quod ut est vel quis ducimus, eveniet, iure dolore
    excepturi in ipsam possimus rem sed eum nemo. Debitis, eaque culpa!
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
  background-color: blue;
}
</style>