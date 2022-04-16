<template>
  <footer>
    <div class="container-fluid">
      <div class="row justify-content-center align-items-center h-vh-50 py-5">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="social-media mb-5">
              <img class="navbar-image d-block mx-auto mb-5" src="@/assets/source/image/logo.svg" alt="Logo">
              <div class="d-flex justify-content-center align-items-center">
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-facebook-f"></i>
                </router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-twitter"></i>
                </router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-youtube"></i>
                </router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-google-plus-g"></i>
                </router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-pinterest"></i>
                </router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-instagram"></i>
                </router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fas fa-envelope"></i>
                </router-link>
              </div>
            </div>
            <div class="copyright d-block d-lg-flex justify-content-center align-items-center text-center">
              <p class="mp-0 text-fade-1">
                &copy; 2021 Triump Motorcycle
              </p>
              <ul class="text-uppercase d-inline mp-0">
                <li class="px-4 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">test ride
                  </router-link>
                </li>
                <li class="px-4 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">dealer</router-link>
                </li>
                <li class="px-4 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">brochures
                  </router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>