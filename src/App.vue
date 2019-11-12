<template>
  <div id="app">
    <h1>Hi! I'm <a href="https://www.instagram.com/albfs/ " target="_blank">Alba</a>, an artist based in <a href="https://www.instagram.com/wearecontracollective/" target="_blank">Barcelona</a></h1>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>
body {
  background-image:url(./assets/alba.jpg);
  background-position: center center;
  background-repeat: no-repeat;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
}

h1 {
    left: 25%;
    line-height: 100px;
    margin-top: -100px;
    position: absolute;
    text-align: center;
    top: 45%;
    width: 50%;
    font-size: 4rem !important;
}

a {
  color: #42b983;
}
</style>
