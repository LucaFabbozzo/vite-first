<script>
import Another from "./components/Another.vue";
import AppTitle from "./components/AppTitle.vue";

export default {
  components: { AppTitle, Another },
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
  <app-title />
  <another />
</template>


<style scoped>
.title-app {
  margin-top: 40px;
  text-align: center;
  color: green;
}
</style>