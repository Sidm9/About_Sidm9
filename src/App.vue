<template>
  <div id="app">
    <Sidebar />
    <div class="navBoxes">
      <router-view />
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
  justify-content: center;
  border-style: double;
  width: 100%;
  padding: 10px;
}

#nav {
  border: black 1px solid;
  /* padding: 30px; */
  width: 30%;
  height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.navBoxes {
  width: 70%;
  border: black 1px solid;
}
</style>
