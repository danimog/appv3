<template>
  <div class="hello">
    
    <h2>{{ msg }}</h2>
    <div class="myoverlay mt-5 mb-5">
      <b-container fluid="md">
        
          <b-row>
            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/hiking.png"></div>
              </b-link>
              <div><span class="h1">Hiking</span></div>
            </b-col> 
            
            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/running.png"></div>
              </b-link>
              <div><span class="h1">Running</span></div>
            </b-col> 

            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/biking.png"></div>
              </b-link>
              <div><span class="h1">Biking</span></div>
            </b-col> 

            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/family.png"></div>
              </b-link>
              <div><span class="h1">Family</span></div>
            </b-col> 
        
            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/nordic.png"></div>
              </b-link>
              <div><span class="h1">Nordic Walking</span></div>
            </b-col> 
        
            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/parco.png"></div>
              </b-link>
              <div><span class="h1">Il Parco</span></div>
            </b-col> 
        
            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/borghi.png"></div>
              </b-link>
              <div><span class="h1">Borghi</span></div>
            </b-col> 
        
            <b-col sm="4" md="4" lg="3">
              <b-link href="#">
                <div><img class="img-fluid w-100" alt="Vue logo" src="../assets/images/icons_w/card.png"></div>
              </b-link>
              <div><span class="h1">La Card</span></div>
            </b-col> 
        
        
          </b-row>
        
      </b-container>
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
