<template>
  <div class="footer mt-auto mb-2">
    <ul class="d-flex">
        <li>
          <a href="" id="patreon">Patreon</a>
        </li>
        <li>
          <a href="">Collaborations</a>
        </li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

ul {
  justify-content: space-evenly;
  list-style: none;
  padding: 0;
  margin: 0;
}

#patreon {
  color: #b94242;
}

a, a:hover {
  color: #42b983;
  text-decoration: none;
  cursor: pointer;
}

</style>
