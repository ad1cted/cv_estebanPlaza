<template>
  <div id="app" class="main">
    <CV nombre="Esteban Isaias Plaza A."/>
  </div>
</template>
<script>

import CV from './components/CV.vue'

export default {
  name: 'App',
  components: {
    CV
  },

}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
