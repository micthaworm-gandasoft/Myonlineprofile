<template>
<div class="container col m12 l12 ">
  <div class="row">
    <div class="col s12 m12">
      <div class="card z-depth-2">
        <div class="card-content left-align">
          <h4  class="blue-grey-text lighten-2" >About Me</h4>
          <p v-for="paragraph in about">
            {{paragraph}}
          </p><br/>
          
        </div>
   </div>
    </div>
  </div>
  <div class="row workexperience">
    <div class="container col m12 s12">
   <work-experience-component :experience="experience"></work-experience-component>
  </div>
  </div>
</div>
</template>
<script>
import WorkExperienceComponent from'./WorkExperienceComponent.vue'
export default {
    name: 'AboutComponent',
    components:{
        WorkExperienceComponent
    },
    props:{
      about:[],
      experience:[]
    }
}
</script>
<style  scoped>
 .workexperience{
   padding:auto;
 }

</style>`