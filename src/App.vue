<template>
  <div id="app">

  <div>
    <h1>Thurman Thoma</h1>
    <main-header></main-header>
  </div>

  <div>
    <project-list></project-list>
  </div>

  <div>
    <main-footer></main-footer>
  </div>
  
  </div>
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
  },
  data() {

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
