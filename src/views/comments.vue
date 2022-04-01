<template>
  <div>
    <div class="main-contant flex-view">
      <searchButton />
       <filterButton />
      <SearhCourses />
      <useraccount />
    </div>
  </div>
</template>



<script>
import searchButton from "../views/searchButton.vue";
import SearhCourses from "../views/SearhCourses.vue";
import filterButton from "../views/filterButton.vue";
import useraccount from "../views/useraccount.vue";
export default {
  name: "comments ",

  components: {
    searchButton,
    SearhCourses,
    filterButton,
    useraccount,
  },
};
</script>



<style src="./comments.css" scoped>
</style>