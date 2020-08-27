<template>
  <div id="app">
    <Profile></Profile>
    <GridImages></GridImages>

    <router-view/>
  </div>
</template>

<script>
import Profile from '@/components/Profile'
import GridImages from '@/components/GridImages'

export default {
  name: 'App',
  components: {
    Profile,
    GridImages
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 2em
}
</style>
