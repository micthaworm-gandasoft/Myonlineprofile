<template>  
  <div class="row">
    <div class="col s12 m12">
      <div class="card z-depth-2">
        <div class="card-title">Skills</div>
        <div class="card-content left-align">
          <ul class="browser-default">
            <li>Linux Server hardening</li>
            <li>  C++/C</li>
            <li> VB.NET</li>
            <li> C#</li>
            <li> Git</li>
            <li>ASP.NET</li>
            <li> Java</li>
            <li>ReactJS</li>
            <li> VueJS</li>
            <li>Restful APIs</li>
            <li>Graph databases and GraphQL</li>
            <li>Python</li> 
            <li> SOA</li>
            <li>Outsystems</li>
            <li>DevOps Tools
                <ul class="browser-default">
                  <li>Docker</li>
                  <li>Kubernetes</li>
                  <li>Jenkins</li>
                </ul>
            </li>
            <li> AWS Code pipeline</li>
            <li> Cloud native development</li>
            <li>Kotlin</li>
            <li>AWS</li>
            <li> IaC Tools
                <ul class="browser-default">
                  <li>AWS CloudFormation</li>
                  <li>Terraform</li>
                  <li>Serverless Framework</li>
              </ul>
            </li>
          </ul>
        </div>
        
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:'SkillsComponent'
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