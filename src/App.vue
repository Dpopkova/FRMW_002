<template>
  <div id="app">
    <input v-model="text"/>
    <input v-model="text"/>
  </div>
</template>

<script>
export default {
  name: 'App',
  data: function() {
    return {
      text: ""
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: black;
  margin-top: 10px;
  display: flex;
  flex-direction: column;
  width: 500px;
}
</style>
