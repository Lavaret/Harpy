<template>
  <div class="wrapper">
    <h1>Harpy</h1>
    <p class="poem">
      His surreal <br />
      yet physical form <br />
      Stands like proud warrior <br />
      before the storm
    </p>
  </div>
</template>

<script>
export default {
  name: 'HeroImage',
}
</script>

<style type="css" scoped>
.wrapper {
  height: 900px;
  width: 100%;
  color: white;
  font-family: 'Mr Dafoe', cursive;
  background-image:url('../assets/heroimage.jpg');
  background-repeat: no-repeat;
  background-position: center;
}

.poem {
  position: absolute;
  margin-top: 500px;
  margin-left: 70px;
  font-weight: 200;
  letter-spacing: 3px;
  text-shadow: 10px -5px 15px black;
  font-size: 45px;
}

h1 {
  position: absolute;
  text-shadow: 5px 0px 20px black;
  margin-top: 100px;
  margin-left: 70px;
  font-size: 200px;
  font-weight: 300;
}
</style>
