<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->

      <sidebar />
    </div>
    <router-view />
  </div>
</template>


<script>
import sidebar from "./views/sidebar.vue";
export default {
  name: "App",
  components: {
    sidebar,
  
  },
  
  // data(){
  //   console.log("created")
  // },
  // beforeCreate()
  // {
  //   alert("beforeCreate");
  // },
  // created(){
  //   alert("created")
  // }
};
</script>


