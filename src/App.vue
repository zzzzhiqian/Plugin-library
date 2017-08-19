<template>
  <div id="app">
     <v-header></v-header>
     <sec></sec>
  </div>
</template>

<script>
import header from './components/header/header.vue'

import sec from './components/section/section.vue'

export default {
  name: 'app',
  components: {
    'v-header': header,
    'sec': sec
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;

}
</style>
