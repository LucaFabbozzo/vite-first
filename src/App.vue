<script>
import Another from "./components/Another.vue";
import AppTitle from "./components/AppTitle.vue";
import Button from "./components/Button.vue";

export default {
  components: { AppTitle, Another, Button },
  name: "App",
  data() {
    return {
      title: "Vue - Vite",
    };
  },
};
</script>


<template>
  <div class="title-app">
    <h1>{{ title }}</h1>
  </div>
  <Button />
  <App-title />
  <Another />
</template>


<style scoped>
.title-app {
  margin-top: 40px;
  text-align: center;
  color: green;
}
</style>