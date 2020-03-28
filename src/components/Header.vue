<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <!-- <svg><use href="/../assets/jackie-beecher-card-flower.svg"></svg> -->
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarTogglerDemo02"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
        <ul class="nav nav-pills mr-auto mt-2 mt-lg-0">
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/" exact><a>Home</a></router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/massage"><a>Massage</a></router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/yoga"><a>Yoga</a></router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/acupuncture"><a>Acupuncture</a></router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" li="tag" to="/contact"><a>Contact Us</a></router-link>
          </li>
        </ul>
        
      </div>
    </nav>
  </div>
</template>