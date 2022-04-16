<template>
  <section class="min-vh-100 bg-image-5 position-relative">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="position-absolute top-50 end-0 translate-middle-y p-5 p-xl-8 w-100 w-lg-auto">
              <small class="text-uppercase text-sub-title"></small>
              <h2 class="display-2 fw-bolder text-uppercase ls-xl-10px mb-3">
                journey <br />
                with <br />
                beckham
              </h2>
              <router-link class="d-flex align-items-center text-white text-decoration-none" to="#">
                <i class="fas fa-play-circle icon-button me-3"></i>
                Watch Now
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Watch2Component",
}
</script>