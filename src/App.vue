<template>
  <div id="app">
    <div class="container">
      <img src="./assets/logo.png">
      <img src="./assets/logo.png">
    <router-view></router-view>
    <button type="button" name="button" class="btn btn-primary">Olá Mundo</button>
    </div>    
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style src="./assets/sass/app.scss" lang="sass"></style>
