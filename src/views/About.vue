<template>
  <div class="dev-Panal-background" >
    <div class="main-dashbord flex-view">
      <div class="vedio-page-nav">
        <div>
          <searchButton />
        </div>
        <div>
          <filterButton />
        </div>
        <div>
          <SearhCourses />
        </div>
        <div>
          <clearbutton />
        </div>

        <div>
          <useraccount />
        </div>
      </div>
      <div></div>
    </div>
    <div class="table-heading">
      <downloadsvc />
    </div>
  </div>
</template>


<script>
import searchButton from "../views/searchButton.vue";
import filterButton from "../views/filterButton.vue";
import SearhCourses from "../views/SearhCourses.vue";
import clearbutton from "../views/clearbutton.vue";
import useraccount from "../views/useraccount.vue";
import downloadsvc from "../views/downloadsvc.vue";
// import comments from "../views/comments.vue"
export default {
  name: "About",
  components: {
    searchButton,
    filterButton,
    SearhCourses,
    clearbutton,
    useraccount,
    downloadsvc,
    // comments,
  },
};
</script>

<style src="./About.css" scoped>
</style>
