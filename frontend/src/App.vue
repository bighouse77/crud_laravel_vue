<template>

  <create-component/>

</template>

<script>
import CreateComponent from "@/components/CreateComponent/CreateComponent.vue";

export default {
  name: 'App',
  components: {
    CreateComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
