<template>
  <div id="app">
    <div class="row">
    <div id="header-container" class="col m12 l12">
    <header-component :Header="header"></header-component>
    </div>
    </div>
    <div class="row" id="body">
    <div class="col m8 l8">
   <about-component :about="about" :experience="workexp"></about-component>
   </div>
   <div class="col m4 l4">
     <div class="row">
        <links-component :links="links"></links-component>
     </div>
    <div class="row">
     <skills-component :skills="skills"></skills-component>
    </div>
   </div>
   </div>
  </div>
</template>

<script>

import HeaderComponent from './components/HeaderComponent.vue'
import AboutComponent from './components/AboutComponent.vue'
import LinksComponent from './components/LinksComponent.vue'
import WorkExperienceComponent from './components/WorkExperienceComponent.vue'
import SkillsComponent from './components/SkillsComponent.vue'

export default {
  name: 'App',
 
  components: {
    HeaderComponent,
    AboutComponent,
    LinksComponent,
    WorkExperienceComponent,
    SkillsComponent
  },
  data(){
    return{
      profiledata:{ },
      header:{},
      about:{},
      links:{},
      workexp:{},
      skills:{}
      }
  },
  methods:{
    fetchProfileData:function(){
      axios.get("https://s3.amazonaws.com/courage.gandasoft.com/payload/resume.json").then(response=>{
         this.profiledata=response.data;
         this.header=response.data.Sections.Header
         this.about=response.data.Sections.About
         this.skills=response.data.Sections.Skills
         this.links=response.data.Sections.Links
         this.workexp=response.data.Sections.WorkExperience
        
         
      });
    }
  },
  beforeMount(){
     this.fetchProfileData()
    
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
  margin-left:10px;

}



</style>
