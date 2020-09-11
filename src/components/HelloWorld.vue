<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="myoverlay mt-3">
      <b-container fluid="md">
        <b-list-group>
          <b-row>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="signpost"></b-icon> Hiking</b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="cursor"></b-icon> Running</b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="bicycle"></b-icon> Biking</b-button></b-col>
            <b-col sm="12" md="6" lg="3"><b-button class="w-100 m-2" variant="outline-info"><b-icon icon="people"></b-icon> Family</b-button></b-col>
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
