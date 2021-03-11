/* eslint-disable prettier/prettier */
<template>
  <div class="xcontainer flex">
    <div class="profile spacing" src="../assets/SID.jpg" />
    <div class="name spacing">
      <h1>Siddharth Mishra</h1>

      <div class="breif spacing">
        <p>
          I am a web developer . I specialize in digital strategy, project
          management, and development. <br /><br />
          I have been at this developing websites and Webapps for a good three
          years, and have sharpened my skills working on over 5 projects.
        </p>
      </div>
    </div>
    <div class="icons-container flex spacing">
      <a
        class="fab fa-discord fa-2x icon"
        href="https://discordapp.com/users/361185528626020353/"
        alt="Discord"
      ></a>
      <a
        class="fab fa-github icon fa-2x"
        href="https://github.com/Sidm9/"
        alt="Github"
      ></a>
      <a
        class="fab fa-linkedin icon fa-2x"
        href="https://www.linkedin.com/in/siddharth-mishra-56273b172/"
        alt="LinkedIn"
      ></a>
     
    </div>
    <button class="button spacing" @click="loadResume()">
      Resume
    </button>
    <div class="nav-links flex spacing">
      <div class="spacing link">
        <router-link to="/">
          About
        </router-link>
      </div>
      <div class="spacing link">
        <router-link to="/About">
          Projects
        </router-link>
      </div>
      <!-- <div class="spacing link">
        <router-link to="/contacts">
          Contact
        </router-link> 
      </div>-->
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",

  methods: {
    loadResume: function() {
      // https://drive.google.com/file/d/1cQYzoW-hFkytMArvQH1uTQ2xq1pKpvwY/view?usp=sharing
      // window.open(
      //   LINK ON NEW RESUME
      // );
    }
  }
};
</script>

<style scoped>
.flex {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}
/* .icons-container {
} */
.icon {
  margin-right: 5px;
  width: 35px;
  height: 35px;
}
a {
  text-decoration: none;
  color: inherit;
}
.spacing {
  margin-top: 20px;
}
.name {
  font-family: "HelveticaMedium", Helvetica, sans-serif;
  justify-content: start;
  text-align: left;
  max-width: 300px;
}
.breif spacing {
  margin-top: 5px;
  font-size: 15px;
  text-align: left;
}
.button {
  margin-left: 5px;
  border-radius: 8px;
  width: 95px;
  height: 35px;
  border: 1px solid #42b983;
  outline: none;
}
.button:hover {
  background-color: #42b983;
  color: whitesmoke;
}
.profile {
  background-image: url("../assets/SID.jpg");
  background-size: cover;
  width: 180px;
  height: 180px;
  border-radius: 50%;
  box-shadow: -2px -1px 8px 0px rgba(190, 190, 190, 0.25);
}
.xcontainer {
  /* border: white 5px solid; */
  flex-direction: column;
  width: 100%;
  height: auto;
}
.nav-links {
  text-align: left;
  width: 100%;
  font-size: 1.2em;
  text-decoration: none;
  flex-direction: column;
}
/* .nav-container {
  text-align: left;
} */
.nav-links a {
  text-decoration: none;
  font-weight: bold;
  color: rgba(240, 248, 255, 0.76);
}
.link,
.icon,
.button {
  transition: transform 0.2s;
}
.link:hover,
.icon:hover,
.button:hover {
  transform: scale(1.12);
  text-shadow: 0.3px 0.3px 0.5px #2c3e50;
}

.nav-links a.router-link-exact-active {
  color: #42b983;
  padding-bottom: 2px;
  border-bottom: 1px solid;
}
@media screen and (max-width: 1055px) {
  .flex {
    justify-content: center;
    align-items: center;
  }
  .name,
  .breif spacing {
    text-align: center;
  }
  .nav-links {
    flex-direction: row;
    justify-content: space-evenly;
  }
}
</style>
