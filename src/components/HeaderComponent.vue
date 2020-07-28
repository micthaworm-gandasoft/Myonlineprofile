<template>
 <div class="row" >
    <div class="col s12 m12 l12" >
    <div class="card horizontal z-depth-3 ">
      <div class="row" >
        <div class="col l4 m6 s12" >
            <div class="responsive-img " id="profile-image" >
                <img src="https://s3.amazonaws.com/courage.gandasoft.com/images/profile.png" class="circle"/>
            </div>
        </div>
        <div class="col l8 m6 s12 right-align">
          <div class="card-stacked">
            <div class="card-content">
              <p>
                <h2 class="header  blue-grey-text">Courage Mic Kosana</h2>
              <p>
              <p class="card-title  blue-grey-text lighten-3 row">
                Software engineer | Solutions Architect | DevOps Engineer | Creator | Multi-Cloud Specialist
              </p>
              <p class="row">
                <div class="col l3 m3 s3">
                  <a href="https://github.com/Gandasoft-freelancing">
                    <span class="fa-stack fa-lg">
                      <i class="fa fa-github-alt fa-3x blue-grey-text lighten-3 fa-inverse"></i>
                     </span> 
                  </a>
                </div>
                <div class="col l3 m3 s3">
                 <a href="https://www.linkedin.com/in/mic-kosana-a6b96b93/"><i class="fa fa-linkedin fa-4x blue-grey-text lighten-3" aria-hidden="true"></i></a>
             
                </div>
                <div class="col l3 m3 s3">
                  <a href="https://web.facebook.com/courage.m.kosana">
                    <span class="fa-stack fa-lg">
                      <i class="fa fa-facebook-official fa-3x blue-grey-text lighten-3 fa-inverse"></i>
                    </span> 
                  </a>
                </div>
                <div class="col l3 m3 s3">
                  <a href="https://twitter.com/couragemic">
                   <span class="fa-stack fa-lg">
                      <i class="fa fa-twitter fa-3x blue-grey-text lighten-3 fa-inverse"></i>
                    </span> 
                    </a>
                </div>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>
<script>
export default {
    name: 'HeaderComponent',
}
</script>
<style scoped>

 #profile-image{
margin:  auto;
float: none;
padding:30px;

 }
 
</style>