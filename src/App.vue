<template>
  <div id="App">
    <h1>Hello Vue!</h1>
    <component1></component1>
    <comp2></comp2>
  </div>
</template>

<script>
import component1 from "./components/component1.vue"
import comp2 from "./components/comp2.vue"


export default{
  components: {
    component1: component1,
    comp2: comp2,
  },
  data() {
    return {
      count: 1,
    }
  },
}


</script>

<style>
  
</style>
