<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <button type="button" name="button" class="btn btn-default">btn-default</button>
    <button type="button" name="button" class="btn btn-info">btn-info</button>
    <button type="button" name="button" class="btn btn-warning">btn-warning</button>
    <button type="button" name="button" class="btn btn-danger">btn-danger</button>
    <button type="button" name="button" class="btn btn-success">btn-success</button>
    <!-- <router-view></router-view> -->
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
