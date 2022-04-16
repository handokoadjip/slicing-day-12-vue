<template>
  <section class="min-vh-100 bg-image-6 position-relative py-5">
    <div class="container position-relative z-999">
      <div class="row mb-5">
        <div class="col-lg-12">
          <div class="wrapper text-center">
            <h2 class="display-6 fw-bolder text-uppercase ls-5px">
              shop classics
            </h2>
          </div>
        </div>
      </div>

      <div class="row justify-content-center my-3">
        <div class="col-lg-9">
          <div class="row">
            <div class="col-lg-2 mb-3 mb-lg-0">
              <div class="wrapper text-center">
                <router-link
                  class="fw-bold text-border-bottom active position-relative text-uppercase text-decoration-none products"
                  to="#">
                  leather jacket
                </router-link>
              </div>
            </div>
            <div class="col-lg-2 mb-3 mb-lg-0">
              <div class="wrapper text-center">
                <router-link
                  class="fw-bold position-relative text-uppercase position-relative text-decoration-none products"
                  to="#">
                  gloves
                </router-link>
              </div>
            </div>
            <div class="col-lg-2 mb-3 mb-lg-0">
              <div class="wrapper text-center">
                <router-link
                  class="fw-bold position-relative text-uppercase position-relative text-decoration-none products"
                  to="#">
                  heans
                </router-link>
              </div>
            </div>
            <div class="col-lg-2 mb-3 mb-lg-0">
              <div class="wrapper text-center">
                <router-link
                  class="fw-bold position-relative text-uppercase position-relative text-decoration-none products"
                  to="#">
                  boots
                </router-link>
              </div>
            </div>
            <div class="col-lg-2 mb-3 mb-lg-0">
              <div class="wrapper text-center">
                <router-link
                  class="fw-bold position-relative text-uppercase position-relative text-decoration-none products"
                  to="#">
                  accesories
                </router-link>
              </div>
            </div>
            <div class="col-lg-2 mb-3 mb-lg-0">
              <div class="wrapper text-center">
                <router-link class="fw-bold text-fade-1 text-uppercase text-decoration-none" to="#">
                  gifts
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-1 mt-5">
          <div class="position-relative h-100 customPrevBtn">
            <div class="position-absolute top-50 start-50 translate-middle h1 pointer">
              <i class="fas fa-arrow-left"></i>
            </div>
          </div>
        </div>

        <div class="col-3 mt-5" v-for="(list, index) in lists" :key="index" :id="list.name">
          <div class="owl-carousel owl-theme" id="products">
            <div class="item">
              <div class="card bg-transparent p-3 text-center h-100">
                <div class="card-body">
                  <figure class="m-0">
                    <img class="w-100" :src="list.image" :alt="list.name" />
                    <figcaption>
                      <h3 class="h5 text-center text-uppercase ls-5px">
                        {{list.name}}
                      </h3>
                    </figcaption>
                  </figure>
                  <p class="m-0 text-fade-1 mb-3">{{list.price}}</p>
                  <router-link :to="list.to">
                    <i class="fas fa-plus-circle icon-button"></i>
                  </router-link>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-1 mt-5">
          <div class="position-relative h-100 customNextBtn">
            <div class="position-absolute top-50 start-50 translate-middle h1 pointer">
              <i class="fas fa-arrow-right"></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ShopComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/jacket-1.png"),
          name: "manchaster",
          price: "$ 340",
          to: "#",
        },
        {
          image: require("@/assets/source/image/jacket-2.png"),
          name: "kate jacket",
          price: "$ 340",
          to: "#",
        },
        {
          image: require("@/assets/source/image/jacket-3.png"),
          name: "rockville",
          price: "$ 340",
          to: "#",
        },
      ]
    }
  }
}
</script>