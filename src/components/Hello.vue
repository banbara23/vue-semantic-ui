<template>
  <div class="hello">
    <div class="ui container">
      <div class="ui labeled button" tabindex="0">
        <div class="ui red button">
          <i class="heart icon"></i> Like
        </div>
        <a class="ui basic red left pointing label">
          1,048
        </a>
      </div>
      <div class="ui labeled button" tabindex="0">
        <div class="ui basic blue button">
          <i class="fork icon"></i> Forks
        </div>
        <a class="ui basic left pointing blue label">
          1,048
        </a>
      </div>
      <div class="ui yellow progress" data-percent="60">
        <div class="bar"></div>
      </div>
      <div class="ui olive progress" data-percent="30">
        <div class="bar"></div>
      </div>
      <div class="ui green progress" data-percent="85">
        <div class="bar"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
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
