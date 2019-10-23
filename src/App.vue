<template>
  <div id="app">
    <HeroImage/>
  </div>
</template>

<script>
import HeroImage from './components/HeroImage.vue';

export default {
  name: 'app',
  components: {
    HeroImage,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Mr+Dafoe&display=swap');

body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
