<template>
  <div class="home flex">
    <div class="main-heading spacing">About</div>
    <div class="spacing"><h1>Biography</h1></div>
    <div class="spacing">
      <p>
        I specialize in digital strategy, project management, and development. I
        have been at this design game for a good three years, and have sharpened
        my skills working on over 5 projects. <br />
        With every project, I implement the highest standards of communication
        and collaboration, and believe that process is the foundation of
        success.
      </p>
    </div>
    <div class="spacing"><h1>Experience</h1></div>

    <div class="exp-container spacing flex">
      <div class="exp-box heading">
        <h3>
          Front End Developer
        </h3>
      </div>
      <div class="exp-box-container ">
        <div class="exp-box flex">
          <h3>
            Lorem Ipsum Dolor ismet
          </h3>
        </div>
        <div class="exp-box subheading flex">
          Aug 2020 - Present
        </div>
        <div class="bullet">
          <li class="exp-box">
            Lorem Ipsum Dolor ismetLorem Ipsum Dolor ismetLorem Ipsum Dolor
            ismetLorem Ipsum Dolor ismet
          </li>
          <li class="exp-box">
            Lorem Ipsum Dolor ismetLorem Ipsum Dolor ismetLorem Ipsum Dolor
            ismetLorem Ipsum Dolor ismet
          </li>
        </div>
        <div class="tech-container">Techstack -> LOGO LOGO LOGO LOGO LOGO</div>
      </div>
    </div>

    <div class="spacing"><h1>Stacks</h1></div>
    <div class="exp-container flex spacing">
      <div>A</div>
      <div>B</div>
      <div>C</div>
      <div>D</div>
      <div>E</div>
      <div>F</div>
    </div>
  </div>
</template>

<script></script>
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
.main-heading {
  font-family: "Lato", sans-serif;
  font-size: 60px;
  font-weight: bold;
  border-style: dotted white;
  margin-bottom: 5px;
}
.exp-container {
  border: 5px red solid;
  width: 100% auto;
  flex-direction: row;
  justify-content: space-around;
}
.heading {
  flex: 0.2;
  flex-wrap: wrap;
  min-width: 200px;
  border: 5px solid white;
}
.exp-box {
  width: auto;
  border: 5px green solid;
}
.bullet {
  display: flex;
  flex-direction: column;
  width: auto;
}
.exp-box-container {
  flex: 0.8;
}
@media screen and (max-width: 600px) {
  .flex {
    /* justify-content: stretch; */
    align-items: center;
  }
  .exp-container {
    flex-direction: column;
    width: auto;
  }
  .heading {
    width: auto;
  }
}
</style>
