<template>
  <h1 class="logoText">CHARACTER FETCH</h1>



  <HelloWorld></HelloWorld>

</template>

<script>

export default {
  name: "NavTemplate",
  components: {
    HelloWorld
  },

}
import HelloWorld from './HelloWorld.vue'
</script>

<style scoped>
.logoText{
  font-family: Unbounded,"PT Serif", serif;
  color:#e8f5ff;
  text-shadow: 2px 2px 5px #004eaa;
}

</style>