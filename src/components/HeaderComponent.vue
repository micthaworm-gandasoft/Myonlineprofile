<template>
 <div class="row" >
    <div class="col s12 m12 l12" >
    <div class="card horizontal z-depth-3 ">
      <div class="row" >
        <div class="col l4 m6 s12" >
            <div class="responsive-img " id="profile-image" >
                <img  :src="Header.ImageUrl" class="circle"/>
            </div>
        </div>
        <div class="col l8 m6 s12 right-align">
          <div class="card-stacked">
            <div class="card-content">
              <p>
                <h2 class="header  blue-grey-text">{{Header.Name}}</h2>
              <p>
              <p class="card-title  blue-grey-text lighten-3 row">
                {{Header.Title}}   </p>
              <p class="row">
                <div class="col l3 m3 s3">
                  <a :href="Header.Sociallinks.Github.Url">
                    <span class="fa-stack fa-lg">
                      <i class="fa fa-github-alt fa-3x blue-grey-text lighten-3 fa-inverse"></i>
                     </span> 
                  </a>
                </div>
                <div class="col l3 m3 s3">
                 <a :href="Header.Sociallinks.linkedIn.Url"><i class="fa fa-linkedin fa-4x blue-grey-text lighten-3" aria-hidden="true"></i></a>
             
                </div>
                <div class="col l3 m3 s3">
                  <a :href="Header.Sociallinks.Facebook.Url">
                    <span class="fa-stack fa-lg">
                      <i class="fa fa-facebook-official fa-3x blue-grey-text lighten-3 fa-inverse"></i>
                    </span> 
                  </a>
                </div>
                <div class="col l3 m3 s3">
                  <a :href="Header.Sociallinks.Twitter.Url">
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
    props:{
      Header:{}
    }
}
</script>
<style scoped>

 #profile-image{
margin:  auto;
float: none;
padding:30px;

 }
 
</style>