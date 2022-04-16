<template>
  <T100BlackComponent />
  <StreetTwinComponent />
  <Watch1Component />
  <Watch2Component />
  <ShopComponent />
  <GalleryComponent />
</template>

<script>
import T100BlackComponent from "@/components/T100BlackComponent.vue";
import StreetTwinComponent from "@/components/StreetTwinComponent.vue";
import Watch1Component from "@/components/Watch1Component.vue";
import Watch2Component from "@/components/Watch2Component.vue";
import ShopComponent from "@/components/ShopComponent.vue";
import GalleryComponent from "@/components/GalleryComponent.vue";

export default {
  name: "HomePage",
  components: {
    T100BlackComponent,
    StreetTwinComponent,
    Watch1Component,
    Watch2Component,
    ShopComponent,
    GalleryComponent,
  },
  mounted() {
    document.title = "Daniel Moulin | Triumph"
  }
}
</script>
