<template>
  <div class="home flex">
    <div class="main-heading spacing">Projects</div>
    <div class="spacing"></div>

    <div class="exp-container spacing flex">
      <div class="card">
        <h2>CODEY</h2>
      </div>

      <div class="img">
        <img
          src="../assets/CODEY.webp"
          width="100%"
          height="100%"
          alt="CODEY"
        />
      </div>
    </div>

    <div class="exp-container spacing flex">
      <div class="card">
        <h2>Founders Hope</h2>
      </div>

      <div class="img">
        <img
          src="../assets/FH.e5957e6d.webp"
          alt="founders Hope"
          width="100%"
          height="100%"
        />
      </div>
    </div>

    <!-- <div class="exp-container spacing flex">
      <div class="card">
        <h2>Uplaw</h2>
      </div>

      <div class="img">
        <img src="" />
      </div>
    </div> -->

    <div class="exp-container spacing flex">
      <div class="card">
        <h2>Glocal Tech Seva</h2>
      </div>

      <div class="img">
        <img
          src="../assets/Glocal.7d07e64d.webp"
          width="100%"
          height="100%"
          alt="glocal tech seva"
        />
      </div>
    </div>

    <div class="exp-container spacing flex">
      <div class="card">
        <h2>SkillSanta</h2>
      </div>

      <div class="img">
        <img
          src="../assets/SKSanta.webp"
          width="100%"
          height="100%"
          alt="skillsanta"
        />
      </div>
    </div>

    <div class="exp-container spacing flex">
      <div class="card">
        <h2>CovHelp</h2>
      </div>

      <div class="img">
        <img
          src="../assets/covhelp.webp"
          width="100%"
          height="100%"
          alt="covHelp"
        />
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
.card {
  display: flex;
  flex: 0.5;
  padding: 10px 10px 10px 10px;
}

.img {
  flex: 0.6;
  height: inherit;
}
.img,
.img > img {
  border-top-right-radius: 8px;
  border-bottom-right-radius: 8px;
}
.exp-container {
  border: 2px aquamarine solid;
  box-shadow: 2px 7px 13px 2px rgba(127, 255, 212, 0.055);
  border-radius: 8px;
  width: 100%;
  flex-direction: row;
  align-items: center;
  transition: 1s all;
  justify-content: center;
}

.exp-container:hover {
  transform: scale(1.07);
}
.main-heading {
  font-size: 60px;
  font-weight: bold;
  margin-bottom: 5px;
}
</style>
