<template>  
  <div class="row">
    <div class="col s12 m12">
      <div class="card z-depth-2">
        <div class="card-title">Skills</div>
        <div class="card-content left-align">
          <ul class="browser-default" v-for="skill in skills">
            <li>{{skill}}</li>
            
          </ul>
        </div>
        
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:'SkillsComponent',
    props:{
      skills:{}
    }
}
</script>
<style  scoped>
.row{
  margin-right:10px;
}


/* not specific enough to put default back */
ul.browser-default {
  list-style-type: initial;
}
</style>