<template>
  <div id="app">
    <div>
      <Echarts></Echarts>
    </div>
    
      <Echarts1></Echarts1>
    
  </div>
</template>

<script>
import Echarts from './components/Echarts'
import Echarts1 from './components/Echarts1'

export default {
  name: 'app',
  components: {
    Echarts,
    Echarts1
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
