<template>
  <section class="info-table-section">
    <div class="info-table-wrapper">
      <div class="column">
        <p><b>Life span:</b> 25 to 35 years</p>
        <p><b>Height:</b> 89cm to 105cm</p>
        <p><b>Weight:</b> Female, 6.3 to 9 kg; male, 3.8 to 5.4 kg</p>
        <p><b>Wingspan:</b> Up to 2 meters</p>
      </div>
      <div class="column">
        <p>The harpy eagle is the national bird of <b>Panama</b>.</p>
        <p>
          Early South American explorers <br />
          named these great birds after <b>Harpyja</b>, <br />
          the predatory half-woman, <br />
          half-bird monster of Greek mythology.</p>
      </div>
    </div>
    <div class="gray-section">
      <p>
        The deadly talons of a harpy eagle can exert 50kg of pressure,<br />
        crushing the bones of its prey and instantly killing its victim.
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'InfoTable',
}
</script>

<style type="scss" scoped>
.info-table-section {
  margin-top: 100px;
  font-family: 'Heebo', sans-serif;
  font-size: 30px;
}

.info-table-wrapper {
  width: 100%;
  height: 500px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.gray-section {
  height: 700px;
  width: 100%;
  background-color: #ced2d5;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
  font-size: 50px;
  letter-spacing: 4px;
}
</style>
