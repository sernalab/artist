<template>
  <div id="app" class="text-center cover-container d-flex w-100 h-100 mx-auto flex-column">
    <Main />
    <Footer />
  </div>
</template>

<script>
import Footer from '@/components/Footer'
import Main from '@/components/Main' 

export default {
  name: 'app',
  components: {Footer, Main}
}
</script>

<style src="./assets/styles.css" lang="css">
#app {
  font-family: 'Roboto', sans-serif;
  color: white;
}
</style>
