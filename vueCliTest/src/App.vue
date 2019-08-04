<template>
  <div id="app">
    <img src="./assets/logo.png">
      <router-view/>
      <router-link to="/">首页</router-link>|
      <router-link to="/Hi">Hi页面</router-link>|
      <router-link :to="{name:'Hi1',params:{userName:'Bella Wong',id:'8888'}}">Hi1页</router-link>|
      <router-link to="/Hi/Hi2">Hi2页</router-link>
      <p>{{$route.name}}</p>

  </div>

</template>

<script>
export default {
  name: 'App'
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
