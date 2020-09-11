<template>
  <div class="hello">
    <h2>{{ msg }}</h2>
    <div class="myoverlay mt-3">
      <b-container fluid="md">
        <b-list-group>
          <b-row>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="signpost" font-scale="3"></b-icon> <span class="h1">Hiking</span></b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="cursor" font-scale="3"></b-icon> <span class="h1">Running</span></b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="bicycle" font-scale="3"></b-icon> <span class="h1">Biking</span></b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="people" font-scale="3"></b-icon> <span class="h1">Family</span></b-button></b-col>
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
h3 {
  margin: 40px 0 0;
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
