<template>
  <div id="app">
    <h2>预祝大家前程似锦</h2>
    <h2>加油02！HelloWorld!</h2>
    <img src="https://pic.sogou.com/d?query=%E9%AC%BC%E7%81%AD%E4%B9%8B%E5%88%83&forbidqc=&entityid=&preQuery=&rawQuery=&queryList=&st=&did=3">
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
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
