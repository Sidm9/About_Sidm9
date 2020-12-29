<template>
  <div class="home flex">
    <div class="main-heading spacing">Projects</div>
    <div class="spacing"></div>

    <div class="exp-container spacing flex">
      <div class="exp-box heading">
        <h3>
          Front End Developer
        </h3>
      </div>

      <div class="exp-box-container ">
        <div class="exp-box">
          <h3>
            Lorem Ipsum Dolor ismet
          </h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.flex {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
.spacing {
  margin-top: 20px;
}

.heading {
  flex: 0.3;
}

.exp-container {
  /* border: 5px red solid; */
  width: 100%;
  flex-direction: row;
  align-items: sa;
  justify-content: space-around;
}

.exp-box {
  /* border: 1px solid black; */
}
.exp-box-container {
  flex: 0.7;
}

.main-heading {
  font-size: 60px;
  font-weight: bold;
  margin-bottom: 5px;
}
</style>
