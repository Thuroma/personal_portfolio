<template>
  <div id="app">
    <div class="content">
    
    <div class="row fixed-bottom">
    <div class="row" id="content-block">
    <div class="col">
      <div>
        <project-list></project-list>
      </div>
    </div>
    </div>

    <div class="col">
      <div class="footer">
        <main-footer></main-footer>
      </div>
    </div>
    </div>

    </div>
  </div>
</template>

<script>
import MainFooter from './components/MainFooter.vue'
import ProjectList from './components/ProjectList.vue'

export default {
  name: 'App',
  components: {
    ProjectList,
    MainFooter,
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
  width: 100vw;
  background-image: url(assets/background_image.jpg);
  overflow: auto;
}

.header, .footer {
  border-radius: 5px;
  height: 80px;
  padding: 10px;
  text-align: left;
  flex: none;
}

</style>
