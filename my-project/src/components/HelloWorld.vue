<template>
  <div class="hello">
    <div v-html="{msg}"></div>
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
  </div>

</template>

<script>
export default {
  name: 'Hello， 会文',
  data () {
    return {
      msg: '欢迎主人！张会文'
    }
  }

}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
</style>
