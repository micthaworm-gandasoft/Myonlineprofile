<template>
  <div id="app">
    <div class="row">
    <div id="header-container" class="col m12 l12">
    <header-component></header-component>
    </div>
    </div>
    <div class="row" id="body">
    <div class="col m8 l8">
   <about-component></about-component>
   </div>
   <div class="col m4 l4">
     <div class="row">
        <links-component></links-component>
     </div>
    <div class="row">
     <skills-component></skills-component>
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
  }
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
