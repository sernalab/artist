<template>
  <div id="app">
    <Main />
    <Footer />
  </div>
</template>

<script>
import Footer from '@/components/Footer' 

export default {
  name: 'app',
  components: Footer
}
</script>

<style>
html {
  background: url(./assets/alba.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
#app {
  font-family: 'Roboto', sans-serif;
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
@media (min-width: 700px) { 
  h1 {
    font-size: 2rem !important;
  }
}

a {
  color: #42b983 !important;
}
</style>
