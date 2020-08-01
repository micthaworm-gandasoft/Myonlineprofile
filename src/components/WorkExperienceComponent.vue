<template>
  <div class="row">
    <div class="col s12 m12 l12">
      <div class="card z-depth-2">
        <h4 class="blue-grey-text lighten-3 center-align">Employment History</h4>
        <div class="card-content">
          <div class="left-align">
            <ul class="z-depth-0">
              <li v-for="exp in experience">
                <div class="row">
                  <h5 class="left-align col l4 m4 s12">{{exp.CompanyName}}</h5>
                  <p class="card-title center-align col l4 m4 s12">{{exp.Role}}</p>
                  <h6 class="right-align col l4 m4 s12">{{exp.YearFrom}}-{{exp.YearTo}}</h6>
                </div>
                <ul class="browser-default" v-for="duty in exp.Responsibilities">
                  <li>{{duty}}</li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import M from "materialize-css";
export default {
  name: "WorkExperienceCompoment",
  props: {
    experience: [],
  },
  mounted() {
    M.AutoInit();
  },
};
</script>
<style scoped>
.collapsible {
  border-style: none;
}
</style>