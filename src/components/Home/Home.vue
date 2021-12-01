<template>
  <div class="content">
    <VueSlickCarousel v-bind="settings">
      <img src="../../assets/carousel-1.png" />
      <img src="../../assets/carousel-2.png" />
      <img src="../../assets/carousel-3.png" />
    </VueSlickCarousel>
    <div class="menu" style="padding-top: 50px; padding-left: 80px">
      <div class="row text-center">
        <div class="col-md">
          <div class="items-menu" style="margin-left: -100.2px">
            <span class="item">Burger </span>
            <span class="item" style="padding-left: 30px">Pastas </span>
            <span class="item" style="padding-left: 30px">Salads </span>
            <span class="item" style="padding-left: 30px">Ice Cream </span>
            <span class="item" style="padding-left: 30px">Cakes </span>
            <span class="item" style="padding-left: 30px">Sav </span>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row ">
        <div class="col-md text-center">
          <div class="card" style="width: 25rem; height: 157px;background:rgb(58 56 62); box-shadow: 0 4px 8px 0 rgba(0,0,0,0.5);">
            <div class="card-body">
             
            </div>
          </div>
          
        </div>
        <div class="col-md text-center">
          <div class="card" style="width: 25rem; height: 157px;background:rgb(58 56 62); box-shadow: 0 4px 8px 0 rgba(0,0,0,0.5);">
            <div class="card-body">
            <img src="../../assets/AmazonikaBurger-AMZ-min-1024x785.png" style="width: 150px;height: 125px;padding-bottom: 10px;margin-right: 220px;">  
            </div>
          </div>
          
        </div>
        <div class="col-md text-center">
          <div class="card" style="width: 25rem; height: 157px;background:rgb(58 56 62); box-shadow: 0 4px 8px 0 rgba(0,0,0,0.5);">
            <div class="card-body">
              
            </div>
          </div>
          
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "./Home.css";
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "Home",
  components: { VueSlickCarousel },
  data() {
    return {
      settings: {
        arrows: true,
        dots: true,
        autoplay: true,
        fade: true,
      },
    };
  },
  methods: {},
  mounted() {},
};
</script>
