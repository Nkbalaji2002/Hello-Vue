<script>
import HelloWorld from "./components/HelloWorld.vue";
export default {
  components: { HelloWorld },
};
</script>

<!-- html -->
<template>
  <div id="app">
    <HelloWorld />
  </div>
</template>

<style>
#app {
  display: flex;
  align-items: center;
  justify-content: center;
  max-width: 400px;
  margin: 0 auto;
  min-height: 100vh;
}
</style>
