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
    Sidebar,
  },
};
</script>
<style>
* {
  margin: 0px;
  background-color: #20262c;
}
#app {
  text-align: center;
  color: whitesmoke;
  margin-top: 50px;
  margin-bottom: 50px;
  display: flex;
  justify-content: center;
}
.container {
  display: flex;
  width: auto;
  border: 5px yellow ridge;
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
  width: auto;
  border: blue 10px solid;
}

@media screen and (max-width: 600px) {
  #sidebar-container,
  #app {
    width: auto;
  }
  .sidebar-container {
    width: auto;
  }
}
</style>
