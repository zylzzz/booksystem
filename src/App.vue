<template>
  <div id="app">
    <comp></comp>
    <router-link to="/">点我</router-link><br/>
    <router-link to="/login">切换</router-link>
    <router-view></router-view>
  </div>
</template>

<script>

import comp from './components/comp.vue'
export default {
  name: 'app',
  components: {
    comp
  },
  data:function(){return {msg:"hello"}}
}
</script>

<style>
#app {
  
}
</style>
