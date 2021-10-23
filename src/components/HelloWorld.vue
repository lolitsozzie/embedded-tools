<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>essential links</h3>
    <ul>
      <li><a href="https://twitter.com/ozzie_martin" target="_blank" rel="noopener">twitter</a></li> | 
      <li><a href="https://www.instagram.com/ozzie_martin/" target="_blank" rel="noopener">instagram</a></li> | 
      <li><a href="https://www.linkedin.com/in/ozzie-martin-a11a14166/" target="_blank" rel="noopener">linkedin</a></li> | 
      <li><a href="https://ozzie.codes" target="_blank" rel="noopener">personal</a></li>
    </ul>
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
