<template>
  <div id="child1" class="component">
    
    <h2>Child 1 Component</h2>
    <span>{{message}}</span>
  </div>
</template>

<script>
export default {
  props: ['message']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#child1 {
  background-color: lightseagreen;
  
}
</style>
