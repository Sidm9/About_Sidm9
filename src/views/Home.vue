<template>
  <div class="home flex">
    <div class="main-heading spacing">About</div>
    <div class="spacing"><h2>Biography</h2></div>
    <div class="spacing">
      <p>
        I specialize in digital strategy, project management, and development. I
        have been at this design game for a good three years, and have sharpened
        my skills working on over 5 projects. <br /> <br />
        With every project, I implement the highest standards of communication
        and collaboration, and believe that process is the foundation of
        success.
      </p>
    </div>
    <div class="spacing"><h2>Experience</h2></div>

    <div class="exp-container spacing flex">
      <div class="exp-box heading">
        Front End Developer
      </div>
      <div class="exp-box-container ">
        <div class="exp-box flex">
          <h3>
            Lorem Ipsum Dolor ismet
          </h3>
        </div>
        <div class="exp-box subheading flex" style="margin-top:5px">
          Aug 2020 - Present
        </div>
        <div class="bullet">
          <li class="exp-box spacing">
            Lorem Ipsum Dolor ismetLorem Ipsum Dolor ismetLorem Ipsum Dolor
            ismetLorem Ipsum Dolor ismet
          </li>
          <li class="exp-box spacing">
            Lorem Ipsum Dolor ismetLorem Ipsum Dolor ismetLorem Ipsum Dolor
            ismetLorem Ipsum Dolor ismet
          </li>
        </div>
        <div class="tech-container spacing flex">
          <div>
            Technologies:
          </div>
          <div>
            <a class="fab fa-react fa-2x" style="color:#61DBFB"></a>
            <a class="fab fa-vuejs fa-2x" style="color:#41B883"></a>
            <a class="fab fa-css3 fa-2x" style="color:#264de4"></a>
            <a class="fab fa-python fa-2x" style="color:#4B8BBE"></a>
          </div>
        </div>
      </div>
    </div>

    <div class="spacing"><h2>Stacks</h2></div>
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
  font-size: 3em;
  font-weight: bolder;
  margin-top: 15px;
  margin-bottom: 5px;
}
.exp-container {
  /* border: 5px red solid; */
  min-width: 300px;
  flex-direction: row;
  justify-content: space-around;
}
.heading {
  font-size: 1.17em;
  font-weight: bold;
  color: aquamarine;
  flex: 0.2;
  flex-wrap: wrap;
  border-left: 1px aquamarine solid;
  min-width: 200px;
  border-radius: 1px;
  padding-left: 6px;
}
.subheading {
  color: rgb(184, 184, 184);
}
.exp-box {
  width: auto;
  /* border: 5px green solid; */
}
.bullet {
  display: flex;
  flex-direction: column;
  width: auto;
  list-style: none;
}
li::before {
  content: "\00BB";
  font-size: 1.3em;
  color: aquamarine;
}
.exp-box-container {
  flex: 0.8;
}
.tech-container {
  align-items: center;
  justify-content: space-between;
  flex-direction: row;
}
@media screen and (max-width: 1027px) {
  .exp-container {
    flex-direction: column;
    width: auto;
  }
  .heading {
    width: auto;
  }
  .exp-box {
    margin-top: 20px;
  }
}

@media screen and (max-width: 400px) {
  .exp-container {
    min-width: auto;
  }
}
</style>
