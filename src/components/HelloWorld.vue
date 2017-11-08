<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Basics</h2>
    <ul>
      <li>clean car trunk</li>
      <br>
      <li>sweep living room</li>
      <br>
      <li>program this</li>
      <br>
    </ul>
    <h2>Work-related</h2>
      <li>call Medical</li>
      <br>
      <li>call union</li>
      <br>
    <!-- <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'My To Do List'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body{
  background-color: yellow;
}
h1, h2 {
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
