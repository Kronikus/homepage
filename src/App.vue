<template>
  <div id="app">

        <router-link to="/" exact>
          <img class="logo" src="./assets/logo.png">
        </router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/services">Services</router-link>
        <router-link to="/contact">Contact</router-link>
        <transition name="fade" mode="out-in">
          <router-view class="view"> </router-view>
        </transition>
       
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {

  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color:aquamarine;
  height: 57px;
  left: 0px;
  right: 0px;
  top:0px;
  position:fixed;
  z-index:999;

}
.logo {
      height: 56px;
      margin-right:10px;
      display: inline-block;
      vertical-align:middle;
      };
</style>
