<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <Techne/>
  </div>
</template>

<script>
import Techne from './components/Techne'

export default {
  name: 'App',
  components: {
    Techne
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  @import "../static/css/reset.css";
  #app {
    width:100%;
    height: 100%;
    & > div:nth-child(1){
      width:100%;
      height: 100%;
    }
  }
</style>
