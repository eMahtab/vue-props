<template>
  <div id="child2" class="component">
    
    <h2>Child 2 Component</h2>
    <span>{{message}}</span>
  </div>
</template>

<script>
export default {
  props:['message']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#child2 {
  background-color: lightcoral;
}

</style>
