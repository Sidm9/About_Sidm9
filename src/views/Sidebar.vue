/* eslint-disable prettier/prettier */
<template>
  <div class="xcontainer flex">
    <div class="profile spacing" />
    <div class="name spacing">
      <h1>Siddharth Mishra</h1>
    </div>
    <div class="breif">
      <p>
        Lorem ipsum is placeholder text commonly used in the graphic, print, and
        publishing industries for previewing layouts and visual mockups.
      </p>
    </div>
    <div class="icons-container flex spacing">
      <div class="icon">Github</div>
      <div class="icon">Discord</div>
      <div class="icon">LinkedIn</div>
    </div>
    <button class="button spacing">
      Resume
    </button>
    <div class="nav-links flex spacing">
      <div class="spacing">
        <router-link to="/">
          Home
        </router-link>
      </div>
      <div class="spacing">
        <router-link to="/About">
          About
        </router-link>
      </div>
      <div class="spacing">
        <router-link to="/contacts">
          Contact
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
};
</script>

<style scoped>
.flex {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}
.breif {
  max-width: ;
  margin-top: 5px;
}
/* .icons-container {
} */
.icon {
  margin-right: 5px;
}
.spacing {
  margin-top: 20px;
}
.breif {
  font-size: 15px;
  text-align: left;
}
.profile {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: white 1px solid;
}
.xcontainer {
  /* border: white 5px solid; */
  flex-direction: column;
  width: 100%;
  height: 80vh;
}
.nav-links {
  text-align: left;
  text-decoration: none;
  flex-direction: column;
}
/* .nav-container {
  text-align: left;
} */
.nav-links a {
  font-weight: bold;
  color: #2c3e50;
}
.nav-links a.router-link-exact-active {
  color: #42b983;
}
@media screen and (max-width: 800px) {
  .flex {
    justify-content: center;
    align-items: center;
  }
  .breif {
    text-align: center;
  }
}
</style>
