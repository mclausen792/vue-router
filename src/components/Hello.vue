<template>
  <div class="hello">
    <h1>Makayla Clausen</h1>
    <h2>{{ msg }}</h2>
    <img src = "../assets/me.jpg" />
    <h2>My Projects</h2>
    <ul>
      <li><a href="https://my-react-2b03f.firebaseapp.com/" target="_blank">React Inbox</a></li>
      <li><a href="https://first-64-project.firebaseapp.com/" target="_blank">Inspire Me</a></li>
      <li><a href="https://galvanizegamers.herokuapp.com/" target="_blank">Galvanize Games</a></li>
      <li><a href="https://rocky-dawn-23084.herokuapp.com/" target="_blank">Galvanize Reads</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to my Web Page!'
    }
  }
}
</script>

<style scoped>
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
img {
width: 90px;
border-radius: 50%;
}
</style>
