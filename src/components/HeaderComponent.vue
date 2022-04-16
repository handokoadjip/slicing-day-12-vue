<template>
  <header class="min-vh-100 bg-image-1 position-relative">
    <nav class="navbar navbar-expand-lg navbar-dark px-5 pb-0">
      <div class="container-fluid">
        <router-link class="navbar-brand me-5 v-invisible" to="#">
          <figure class="m-0">
            <img class="navbar-image" src="@/assets/source/image/logo.svg" alt="Logo">
          </figure>
        </router-link>
        <div class="collapse navbar-collapse">
          <div class="d-flex flex-column flex-lg-row justify-content-between w-100">
            <ul class="navbar-nav text-uppercase">
              <li class="nav-item px-4">
                <router-link class="nav-link nav-link-sub fs-7 fw-bold" to="#">test ride</router-link>
              </li>
              <li class="nav-item px-4">
                <router-link class="nav-link nav-link-sub fs-7 fw-bold" to="#">dealer</router-link>
              </li>
              <li class="nav-item px-4">
                <router-link class="nav-link nav-link-sub fs-7 fw-bold" to="#">brochures</router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-dark px-5 pb-5 pt-0">
      <div class="container-fluid">
        <router-link class="navbar-brand me-5" to="#">
          <figure class="m-0">
            <img class="navbar-image" src="@/assets/source/image/logo.svg" alt="Logo">
          </figure>
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <div class="d-flex flex-column flex-lg-row justify-content-between w-100">
            <ul class="navbar-nav text-uppercase">
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link fw-bold" aria-current="page" to="#">motorcycles</router-link>
              </li>
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link fw-bold" to="#">accesories</router-link>
              </li>
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link fw-bold" to="#">clothing</router-link>
              </li>
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link fw-bold" to="#">offers & services</router-link>
              </li>
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link fw-bold" to="#">inside triumph</router-link>
              </li>
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link fw-bold" to="#">news & event</router-link>
              </li>
            </ul>
            <ul class="navbar-nav text-uppercase">
              <li class="nav-item px-0 px-lg-4">
                <router-link class="nav-link active fs-5" to="#"><i class="fas fa-search"></i></router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
    <div class="position-absolute top-50 end-0 translate-middle-y pe-5 d-none d-lg-block">
      <div class="d-flex flex-column justify-content-center align-items-center me-5">
        <div class="text-rotate circle-bullet my-3"></div>
        <div class="text-rotate circle-bullet my-3"></div>
        <div class="text-rotate circle-bullet-color my-3"></div>
        <div class="text-rotate circle-bullet my-3"></div>
        <div class="text-rotate circle-bullet my-3"></div>
      </div>
    </div>
    <div class="position-absolute top-50 end-0 translate-middle-y pe-6 d-none d-lg-block">
      <div class="d-flex flex-column justify-content-center align-items-center me-5 text-fade-1">
        Truxton
      </div>
    </div>
    <section>
      <div class="container-fluid p-5">
        <div class="row">
          <div class="col-lg-12">
            <div class="wrapper d-flex justify-content-start">
              <div class="position-absolute bottom-0 start-0 p-5 p-xl-8">
                <small class="text-uppercase text-sub-title">trumph speed trpile</small>
                <h1 class="display-2 fw-bolder text-uppercase ls-xl-10px">
                  the icon. <br />
                  redefinded.
                </h1>
                <p class="my-4 text-fade-1">Real poise, Real power, Real performance.</p>
                <router-link to="#">
                  <i class="fas fa-arrow-alt-circle-down icon-button"></i>
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

