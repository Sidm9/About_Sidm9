<template>
  <div id="app">
    <div class="container">
      <div class="sidebar-container">
        <Sidebar />
      </div>
      <div class="navBoxes">
        <router-view />
      </div>
    </div>
  </div>
</template>
<script>
import Sidebar from "./views/Sidebar.vue";
export default {
  components: {
    Sidebar
  }
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@300&display=swap");
* {
  font-family: "Raleway", sans-serif;
  margin: 0px;
  background-color: #121212;
  color: rgba(240, 248, 255, 0.76);
}
#app {
  text-align: center;
  color: rgb(36, 36, 36);
  margin-top: 80px;
  margin-bottom: 50px;
  margin-right: 5%;
  margin-left: 5%;
  display: flex;
  justify-content: center;
}
.container {
  display: flex;
  width: auto;
  /* border: 5px yellow ridge; */
  display: flex;
  flex-wrap: wrap;
  align-items: auto;
  justify-content: center;
}
.sidebar-container {
  width: 400px;
}
.navBoxes {
  flex: 1;
  text-align: left;
  height: auto;
  min-width: 550px;
  max-width: 550px;
}

@media screen and (max-width: 650px) {
  #sidebar-container,
  #app {
    width: auto;
  }

  .sidebar-container,
  .navBoxes {
    width: auto;
    min-width: auto;
  }
}

::-webkit-scrollbar {
  width: 5px;
  height: 5px;
}
::-webkit-scrollbar-thumb {
  background: linear-gradient(13deg, #7fffd4 14%, #32fcb9 64%);
  border-radius: 12px;
}
::-webkit-scrollbar-thumb:hover {
  background: #53edba;
}
::-webkit-scrollbar-track {
  background: #121212;
  border-radius: 15px;
  box-shadow: inset 7px 2px 12px #121212;
}
</style>
