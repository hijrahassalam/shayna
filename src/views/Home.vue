<template>
  <div class="home">
    <header-shayna />
    <carousel-shayna />
    <item-shayna />
    <insta-shayna />
    <partner-shayna />
    <footer-shayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
//import carousel from "vue-owl-carousel";
import CarouselShayna from "../components/CarouselShayna.vue";
import ItemShayna from "../components/ItemShayna.vue";
import InstaShayna from "../components/InstaShayna.vue";
import PartnerShayna from "../components/PartnerShayna.vue";
import FooterShayna from "../components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    //carousel,
    CarouselShayna,
    ItemShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna,
  },
};
</script>
