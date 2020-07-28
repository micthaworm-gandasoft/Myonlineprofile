<template>
<div class="container col m12 l12 ">
  <div class="row">
    <div class="col s12 m12">
      <div class="card z-depth-2">
        <div class="card-content left-align">
          <h4  class="blue-grey-text lighten-2" >About Me</h4>
          <p>With 5 years of experience in full-stack web development, DevOps work and systems
            architecture, I am confident I will be an excellent fit to be a software developer in your
            company. My experience has provided me with the innovative and technical skills
            necessary to successfully provide your company with multifaceted technical solutions
              across a wide range of software platforms.
          </p><br/>
          <p>
            I have been responsible for leading the multi-cloud and multi-platform systems. I have
            been deeply involved in mobile, web based as well as cloud native application, building
            innovative systems architecture via python, C#, HTML5, CSS3/SASS, JavaScript/React,
            MySQL, Docker based microservices, React Native and Elasticsearch. I was instrumental
            in structuring several internal systems comprising order entry/management tools, Chat
            bots, conversion/revenue reporting, and production workflow tracking, as well as designed
            custom REST APIs built in Python, Java, and NodeJS. I also successfully collaborate on
            solutions with our product, QA, and marketing teams to offer the best user experience to
            build higher customer lifetime value. To add to this I have worked with 4IR related projects
            including RPA using UiPath, machine learning internal process stream lining tools for
            Corperates, as well as take part in prestigious events like the AWS game day
            hackathons.
          </p><br/>
          <p>
            I have refined my strengths through six years of experience in DevOps, where I provided
            solutions in database technology, programming, operating systems. The following is a
            snapshot of my broader technical skills, Agile Project Management, Custom Web and Mobile Applications, Database Programming,Data Science, DevOps,MLOps Cloud Native Development (AWS, Azure and GCP)
          <p>I would welcome the chance to provide further insight into my knowledge of project
            management, technical abilities, personal attributes, and track record of success in
            building revenue generating web technologies compatible across multiple platforms,multicloud
            environments, browsers, and devices.
          </p>
        </div>
   </div>
    </div>
  </div>
  <div class="row">
   <work-experience-component></work-experience-component>
  </div>
</div>
</template>
<script>
import WorkExperienceComponent from'./WorkExperienceComponent.vue'
export default {
    name: 'AboutComponent',
    components:{
        WorkExperienceComponent
    }
}
</script>
<style  scoped>


</style>`