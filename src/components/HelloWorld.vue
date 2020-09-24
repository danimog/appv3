<template>
  <div class="hello">
    
    <h2>{{ msg }}</h2>
    <div class="myoverlay mt-5 mb-5">
      <b-container fluid="md">
        <b-list-group>
          <b-row>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-danger"><img class="img-fluid" alt="Vue logo" src="../assets/images/icons_w/hiking.png"><span class="h1">Hiking</span></b-button></b-col> 
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><img class="img-fluid" alt="Vue logo" src="../assets/images/icons_w/running.png"> <span class="h1">Running</span></b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-warning"><img class="img-fluid" alt="Vue logo" src="../assets/images/icons_w/biking.png"> <span class="h1">Biking</span></b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-success"><img class="img-fluid" alt="Vue logo" src="../assets/images/icons_w/family.png"> <span class="h1">Family</span></b-button></b-col>
          </b-row>
        </b-list-group>
      </b-container>
    </div>
    <div>
      
      Footer
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: 40px 0 0;
  color: darkgreen;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
