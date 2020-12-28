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
    Sidebar
  }
};
</script>
<style>
* {
  margin: 0px;
}
#app {
  text-align: center;
  color: #2c3e50;
  display: flex;
  height: 100vh;
  justify-content: center;
}
.container {
  display: flex;
  width: 70%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.navBoxes {
  width: 70%;
  border: black 1px solid;
}
</style>
