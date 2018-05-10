<template>
  <div id="app">
    <img src="./assets/logo.png" id="logo">
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
  text-align: center;
  margin-top: 100px;
  line-height: 30px;
}

#app #logo {
  width: 240px;
  margin-bottom: 50px;
}
</style>
