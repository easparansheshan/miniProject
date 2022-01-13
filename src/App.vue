<template>
  <!-- Social Media Bar -->

  <div id="nav">
    <span id="name">Tourist places in Srilanka</span>
    <router-link :class="{ active: $route.name === 'Home' }" to="/"
      >Home</router-link
    >
    |
    <router-link :class="{ active: $route.name === 'Gallery' }" to="/Gallery"
      >Gallery</router-link
    >
    <router-link :class="{ active: $route.name === 'Hotels' }" to="/Hotels"
      >Hotels</router-link
    >
    

    <router-link
      :class="{ active: $route.name === 'Contactus' }"
      to="/Contactus"
      >Reminder</router-link
    >

    <router-link :class="{ active: $route.name === 'About' }" to="/About"
      >About</router-link
    >
  </div>
  <router-view />

  <!-- <footer>
    <div id="footer">
      All rights reserved @SHESHAN
    </div>
  </footer> -->

  <!-- Footer -->
  <footer class="text-center text-lg-start background">
    <!-- Section: Social media -->
    <section
      class="
        d-flex
        justify-content-center justify-content-lg-between
        p-4
        border-bottom
      "
    >
      <!-- Left -->
      <div class="me-5 d-none d-lg-block">
        <span>Get connected with us on social networks:</span>
      </div>
      <!-- Left -->

      <!-- Right -->
      <div>
        <a href="https://www.facebook.com/Sheshan.H/" class="me-4 text-reset">
          <i class="fab fa-facebook-f"></i>
        </a>
        <a href="https://twitter.com/EasparanSheshan" class="me-4 text-reset">
          <i class="fab fa-twitter"></i>
        </a>
        
        <a href="https://www.instagram.com/sheshaneasparan/" class="me-4 text-reset">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="https://www.linkedin.com/in/easparan-sheshan-97ba7418a/" class="me-4 text-reset">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="https://github.com/easparansheshan" class="me-4 text-reset">
          <i class="fab fa-github"></i>
        </a>
      </div>
      <!-- Right -->
    </section>
    <!-- Section: Social media -->

    <!-- Section: Links  -->
    <section class="">
      <div class="container text-center text-md-start mt-5">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <h6 class="text-uppercase fw-bold mb-4">
              <i class="fas fa-gem me-3"></i>Hotels.lk
            </h6>
            <p>
              In the Indian Ocean, south of India, Sri Lanka is an island that
              captivates with its great variety of landscapes. From the endless
              tropical beaches, scalloped by palm trees, to the high mountain
              tea plantations, the green exuberance of the humid forests or the
              plateau of arid beauty.
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">Quick Links</h6>
            <p>
              <a href="/" class="text-reset">Home</a>
            </p>
            <p>
              <a href="/gallery" class="text-reset">Gallery</a>
            </p>
            <p>
              <a href="/hotels" class="text-reset">Hotels</a>
            </p>
            <p>
              <a href="/Contactus" class="text-reset">Reminder</a>
            </p>
            <p>
              <a href="/about" class="text-reset">About</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4 mail">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">Contact</h6>
            <p>
              <i class="fas fa-home me-3"></i> 29/1 Arasady pillayar kovil Batti
            </p>
            <p>
              <i class="fas fa-envelope me-3"></i>
              easparansheshan456@gmail
            </p>
            <p><i class="fas fa-phone me-3"></i> + 94 076 716 0699</p>
            <p><i class="fas fa-print me-3"></i> + 94 065 222 4377</p>
          </div>
          
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.9)">
      © 2021 Copyright: EASPARAN SHESHAN
    </div>
    <!-- Copyright -->
  </footer>
  <!-- Footer -->
</template>

<style lang="scss"> 
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

html,
body {
  padding: 0;
  margin: 0;
  overflow-x: hidden;
}
#nav {
  padding: px;
  //width: 100%;
  //  height: 30px;
  background-color: #2c3e50;
  // line-height: 30px;

  a {
    font-weight: bold;
    color: rgb(255, 255, 255);
    text-decoration: none;
    margin: 0 5px 0 5px;
    &.active {
      color: aqua;
    }
  }
}
#name {
  color: white;
  margin-right: 600px;
  font-family: "Licorice", cursive;
  font-size: 30px;
}

#footer {
  min-height: PX;
  bottom: 0;
  padding: px;
  width: 100%;
  height: 30px;
  background-color: #2c3e50;
  color: white;
  line-height: 30px;
}
#social1 {
  margin-left: -800px;
}
#socialBar {
  background-color: #686766;
}
#phone {
  color: white;
}
.background {
  background-color: #2c3e50;
  color: white;
}
</style>
