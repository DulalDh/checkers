<template>
  <div id="app">
    <boardComponent />
  </div>
</template>

<script>
import BoardComponent from "./components/BoardComponent.vue";

export default {
  name: "App",
  components: {
    BoardComponent,
  },
};
</script>
