<template>
  <div id="app">
    <NewComp/>
    <Child2/>
    <router-view/>
  </div>
</template>

<script>
import NewComp from "@/components/New_comp"
import Child2 from "@/components/Child2"

export default {
  name: 'App',
  components:{
    NewComp,
    Child2
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
  margin-top: 60px;
}
</style>
