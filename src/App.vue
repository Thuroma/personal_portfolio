<template>
  <body>
  <div id="app">
  
  <div class="header">
    <main-header></main-header>
  </div>

  <div class="row">

  <div class="col d-flex align-items-center" id="projects">
      <div>
        <project-list></project-list>
      </div>
  </div>

  </div>

  <div class="fixed-bottom footer">
    <main-footer></main-footer>
  </div>

  </div>
  </body>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'
import ProjectList from './components/ProjectList.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    ProjectList,
    MainFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vh;
  width: 100vw;
  background-image: url(assets/wallpaper_background.jpg);
}

.header, .footer {
  border-radius: 5px;
  height: 80px;
  color: #5b8546;
  box-shadow: 0 15px 25px rgba(129, 124, 124, 0.2); 
  backdrop-filter: blur(14px);
  background-color: rgba(255, 255, 255, 0.2); 
  padding: 10px;
  text-align: left;
}

#projects {
  height: 80%;
  width: 100%;
}

.row {
  height: 100%;
  width: 100%;
}


</style>
