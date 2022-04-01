<template>
  <div class="main-popup-div">
    <div class="popup">
      <img class="popup-img" src="../assets/crop.jpg" alt />
      <button class="picture-upload-button">
         <i class="fa fa-camera" aria-hidden="true" style="color:#575757;"></i>
         <input type="file" name="" id="" style="width: 0px;">
       
      </button>
      <!-- <input type="file" name="" id="imageUpload">
       <i class="fa fa-camera" aria-hidden="true" style="color:#575757;"></i>
      <label for="imageUpload"></label> -->
    </div>
    <div>
      <ul class="ul-style">
        <li><h4 style="margin-bottom: 6px; font-weight:bold;">Roni johnson</h4></li>
        <li>NP-12345</li>
        <li>Ronijohnson@gmail.com</li>
        <li>03068556292</li>
      </ul>
    </div>
    <div class="sign-out">
      <i class=" sign-in-icon fa fa-sign-in" aria-hidden="true"></i>
      <p class="sign-out-heading">SIGN OUT</p>
    </div>
  </div>
</template>  


<script>
export default {
  name: "popup",
  
};

</script>



<style src="./popup.css" scoped>
</style>