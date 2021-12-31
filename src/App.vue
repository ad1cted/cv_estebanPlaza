<template>
  <div id="app" class="main">
    <CV nombre="Esteban Isaias Plaza A."/>
    <button-pdf/>

  </div>
</template>
<script>

import CV from './components/CV.vue'
import ButtonPdf from "./components/ButtonPdf";
export default {
  name: 'App',
  components: {
    CV,
    ButtonPdf

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
  margin-top: 20px;
}
</style>
