<script>
export default {
  name: "AppTitle",
  data() {
    return {
      title: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <div class="container">
    <h2>{{ title }}</h2>
  </div>
</template>

<style scoped>
h2 {
  color: #A74EFE;
  text-transform: uppercase;
  font-size: 2rem;
}
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 150px auto;
  width: 50%;
  height: 200px;
  text-align: center;
  background-color: #f2f1ee;
  box-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.3);
  border-radius: 10px;
}
</style>
