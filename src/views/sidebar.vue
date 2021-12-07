<template>
  <div class="sidebar">
    <div class="sidebar-logo">
      <img class="nplogo" src="../assets/NpWhite.svg" alt />
    </div>
    <!-- <div class="sidebar-title">Reporting panel</div> -->
    <ul class="sidebar-list">
      <!-- <li class="sidebar-list-item">
                 <img class="nplogo" src="../assets/NpWhite.svg" alt="">
                Dashboard
      </li>-->
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/dash_icon.svg" />Dashboard
      </li>
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/vr-icon.svg" /> Vedio Reports
      </li>
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/comment-icon.svg" /> Comments Reports
      </li>
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/star-icon.svg" />User Feedback
      </li>
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/feedback-icon.svg" />Vedio Feedback
      </li>
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/quiz-icon.svg" />Quiz Issues
      </li>
      <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/users.svg" />User Starts
      </li>
    </ul>
  </div>
</template>




<script>
export default {
  name: "sidebar",
};
</script>


<style src="./sidebar.css" scoped>
</style>