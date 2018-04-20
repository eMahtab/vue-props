<template>
  <div id="app">
    
      <div class="container">
        <div class="row">
            <div class="col-xs-12">
                <parent></parent>
            </div>
        </div>
    </div>
    
  </div>
</template>

<script>
import Parent from './components/Parent.vue';

export default {
  components:{parent:Parent},
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
div.component {
        border: 1px solid black;
        padding: 30px;
}
</style>
