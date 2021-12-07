<template>
  <div class="slider-scroll">
    <p class="dashboard-heading">Reported Issues Dashboard</p>
    <VueSlickCarousel v-bind="settings">
      <div><Card /></div>
      <div><Card /></div>
      <div><Card /></div>
      <div><Card /></div>
      <div><Card /></div>
      <div><Card /></div>


    </VueSlickCarousel>
     <Chart />
     <graph />
  </div>
</template>
 
<script>

import VueSlickCarousel from "vue-slick-carousel";
import Card from "./Card.vue";  
import Chart from './Chart.vue';
import graph from "../views/graph.vue"
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "MyComponent",
  components: {   
      VueSlickCarousel,
      Card,
      Chart,
      graph

  },


  // props:{
  //   titile: "ronijohnson"
  // },

  data() {
    return {
      settings: {
        arrows: false,
        dots: true,
        slidesToShow: 5,
        slidesToScroll: 5,
      },
    };
  },
};
</script> 

<style src="./reportingIshu.css" scoped></style>

