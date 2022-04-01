<template>
  <div class="sidebar">
    <div class="sidebar-logo">
      <img class="nplogo" src="../assets/NpWhite.svg" alt />
    </div>
    <ul class="sidebar-list">

      <router-link to= "/"  style="    text-decoration: none;" >
        <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/dash_icon.svg" />Dashboard
      </li>
      </router-link>
      
      <router-link to="/about" style="    text-decoration: none;"><li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/vr-icon.svg" /> Videos Reports
      </li></router-link>
      
     <router-link to="/comments" style="text-decoration:none;">
       
        <li class="sidebar-list-item">
        <img class="dash-box-icon" src="../assets/comment-icon.svg" /> Comments Reports
      </li>
       </router-link>
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


data(){
  return{
  
  }
}

};


</script>


<style src="./sidebar.css" scoped>
</style>