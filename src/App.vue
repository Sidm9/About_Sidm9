<template>
  <div id="app">
    <div class="container">
      <Sidebar />
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
}
#app {
  text-align: center;
  color: #2c3e50;
  margin: 50px;
  display: flex;
  flex-wrap: wrap;
  /* height: auto; */
  justify-content: center;
}
.container {
  display: flex;
  width: 70%;
  display: flex;
  align-items: auto;
  justify-content: center;
}
.navBoxes {
  width: 60%;
  text-align: left;
  height: auto;
  border: black 10px solid;
}
</style>
