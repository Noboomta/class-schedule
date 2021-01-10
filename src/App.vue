<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Boom nickname="BOOMMMM" age="19"/>
    <Subject subName="Soft Specification and Design"
      teacherName="Kritsana" day="1"
      startTime="13" endTime="15"
      note="Classroom" work=""/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Boom from './components/Boom.vue'
import Subject from './components/Subject.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Boom,
    Subject
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
