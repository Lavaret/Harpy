<template>
  <div id="app">
    <HeroImage/>
    <InfoTable />
  </div>
</template>

<script>
import HeroImage from './components/HeroImage.vue';
import InfoTable from './components/InfoTable.vue';

export default {
  name: 'app',
  components: {
    HeroImage,
    InfoTable,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Mr+Dafoe&display=swap');
@import url('https://fonts.googleapis.com/css?family=Heebo&display=swap');

body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
