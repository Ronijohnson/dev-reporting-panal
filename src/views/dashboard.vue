<template>
  <div class="main-dashboard flex-view">
    <div>
      <button class="filter-button">
        <i class="filter-icon fa fa-filter adjustIcon positionAdjust" aria-hidden="true"></i>
        <input class="filter-input" type="text" name id placeholder="Filter by market" />

        <i class="angle-drown fa fa-angle-down" aria-hidden="true"></i>
      </button>
    </div>

    <div>
      <button class="search-button">Search</button>
    </div>
    <div>
      <button class="clear-button">CLEAR</button>
    </div>
    <!-- <popup /> -->
  </div>
  
</template>







<script>
// import popup from "../views/popup.vue"
export default {
  name: "dashboard",
  comments:{
        // popup,
  }
};
</script>


<style src="./dashboard.css" scoped>
</style>