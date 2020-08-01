<template>  
  <div class="row">
    <div class="col s12 m12">
      <div class="card z-depth-2 ">
        <div class="card-content black-text">
          <div class="row left-align">
            <div class="col l12 m12 s12 "><i class="fa fa-map-marker blue-grey-text lighten-2 fa-1x" aria-hidden="true"> </i><span class="blue-grey-text linktext" >{{links.Location}}</span></div>
             <div class="col l12 m12 s12 "><i class="fa fa-envelope-o blue-grey-text lighten-2 fa-1x" aria-hidden="true"></i><a href="mailto:courage.kosana@gandasoft.com" class="linktext blue-text darken-1">courage.kosana@gandasoft.com</a></div>
           
          </div>

        </div>
       
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:'LinksComponent',
    props:{
      links:{}
    }
}
</script>
<style  scoped>
.row{
  margin-right:10px;
}
.linktext{
  padding:1em;
}
</style>