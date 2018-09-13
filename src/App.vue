<template>
  <div id="app">
    <div class="">
      <img src="./assets/logo.png" class="banner-img-vue">
      <img src="https://firebase.google.com/_static/5ca761a112/images/firebase/lockup.png">
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.banner-img-vue {
  height: 65px;
  margin-right: 40px;
}
</style>
