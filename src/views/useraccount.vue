<template>
    <div>
       <div class="user-account-icon" @click="openPopup()">
           <i class="fa fa-user-circle-o" aria-hidden="true" style="font-size: 32px;"></i> 
           <div><p style="    padding-left: 8px;    font-family: Open Sans, sans-serif; font-size:14px">Fahad khan</p>
      
           </div>
           
              <popup  v-if="show "/>
              
         
       </div>
 
         
    </div>

</template>




<script>
import popup from "../views/popup.vue"
export default {
    name:"useraccount",
    components:{
         popup,
    },
    data(){
  return{
    show:false
    
  };
},
methods:{
  openPopup(){
    this.show = !this.show;
  }
},
    
}
</script>


<style src="./useraccount.css" scoped>

</style>