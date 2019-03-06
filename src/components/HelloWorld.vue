<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://jsonplaceholder.typicode.com/photos?albumId=1" target="_blank" rel="noopener">album1</a>
      <a href="https://jsonplaceholder.typicode.com/photos?albumId=2" target="_blank" rel="noopener">album2</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=3" target="_blank" rel="noopener">album3</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=4" target="_blank" rel="noopener">album4</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=5" target="_blank" rel="noopener">album5</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=6" target="_blank" rel="noopener">album6</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=7" target="_blank" rel="noopener">album7</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=8" target="_blank" rel="noopener">album8</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=9" target="_blank" rel="noopener">album9</a>
<a href="https://jsonplaceholder.typicode.com/photos?albumId=10" target="_blank" rel="noopener">album10</a>

    </p>
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
