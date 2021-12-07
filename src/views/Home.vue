<template>
  <div class="main-board" >
    <sidebar />
    <dashboard />
    <reportingIshu />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
// import sidebar from "/sidebar.vue";
import sidebar from "../views/sidebar.vue"
import dashboard from "../views/dashboard.vue"
import reportingIshu from "../views/reportingIshu.vue"
export default {
  name: "Home",


  components:{
    sidebar,
    dashboard,
    reportingIshu,
    //  VueSlickCarousel,
  },
};
</script>

<style scoped>
body{
  margin: 0;
    padding: 0;
    overflow-x: hidden;
    box-sizing: border-box;
    overflow-x: hidden;
}
.main-board{
  background-color:#f7f7f7;
  margin-left: 17rem;
}


</style>
