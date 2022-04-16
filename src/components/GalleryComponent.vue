<template>
  <section class="min-vh-100">
    <div class="container-fluid">
      <div class="row justify-content-center align-items-center h-100">
        <div class="col-6 col-lg-3 p-0" v-for="(list, index) in lists" :key="index">
          <figure class="m-0">
            <img class="w-100" :src="list.image" :alt="`gallery-${index}`" />
          </figure>
        </div>

        <div :class="`col-6 p-0 ${lists ? 'col-lg-3' : 'col-lg-12'}`">
          <div class="position-relative">
            <figure class="m-0">
              <img class="w-100 v-invisible" src="@/assets/source/image/gallery-8.jpg" alt="gallery-8" />
            </figure>
            <div
              class="position-absolute top-50 start-50 translate-middle w-100 h-100 last-gallery d-flex justify-content-center align-items-center"
              :style="{'background-image': `url(${require('@/assets/source/image/gallery-8.jpg')})`, 'background-repeat': 'no-repeat', 'background-size': 'cover', 'background-position': 'center'}">
              <div class="text-center position-relative z-999">
                <p class="h3 fw-bold">#</p>
                <h5 class="fs-4 text-uppercase fw-bolder text-white mb-4">
                  triumph <br /> classics
                </h5>
                <p class="m-0 text-fade-1">
                  Become A legend. <br />
                  Hastag your instagram or <br />
                  facebook photo.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "GalleryComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/gallery-1.jpg"),
        },
        {
          image: require("@/assets/source/image/gallery-2.jpg"),
        },
        {
          image: require("@/assets/source/image/gallery-3.jpg"),
        },
        {
          image: require("@/assets/source/image/gallery-4.jpg"),
        },
        {
          image: require("@/assets/source/image/gallery-5.jpg"),
        },
        {
          image: require("@/assets/source/image/gallery-6.jpg"),
        },
        {
          image: require("@/assets/source/image/gallery-7.jpg"),
        },
      ]
    }
  }
}
</script>