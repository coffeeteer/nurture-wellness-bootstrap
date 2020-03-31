<template>
  <div>
    <div class="jumbotron m-0 bg-white">
      <div class="row">
        <div class="col-md-8 col-sm-12">
          <h1 class="display-4 nurture-wellness-title">Nurture Wellness Studio</h1>
        </div>
        <div class="col-md-4 col-sm-12 text-sm-center text-md-right ">
          <address>
            <h5>
              <a href="tel:+8284009616">
                Phone: 828-400-9616
                <i class="fas fa-phone-square-alt"></i>
              </a>
            </h5>
            <h5>
              <a href="mailto:jackiebeecher50@gmail.com">
                jackiebeecher50@gmail.com
                <i class="fas fa-envelope-open-text"></i>
              </a>
            </h5>
            <h5>
              Bryson City, NC
              <i class="fas fa-map-marker-alt"></i>
            </h5>
          </address>
        </div>
      </div>
    </div>
    <!--Navbar  -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="#"><i class="fas fa-spa"></i></a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <!-- Home -->
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/" exact>
              <a>Home</a>
            </router-link>
          </li>
          <!-- Massage  -->
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/massage">
              <a>Massage</a>
            </router-link>
          </li>
          <!-- Yoga -->
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/yoga">
              <a>Yoga</a>
            </router-link>
          </li>
          <!-- Acupuncture -->
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/acupuncture">
              <a>Acupuncture</a>
            </router-link>
          </li>
          <!-- Contact US-->
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/contact">
              <a>Contact Us</a>
            </router-link>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<style>
.nurture-wellness-title {
  font-family: "Alice", serif;
}
</style>