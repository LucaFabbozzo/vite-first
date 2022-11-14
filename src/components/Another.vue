<script>
export default {
  name: "Another",
  data() {
    return {
      main: "altro componente",
    };
  },
};
</script>

<template>
  <div class="container">
    <h3>{{ main }}</h3>
  </div>
</template>


<style scoped>
.container {
  background-color: brown;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 100px auto;
  width: 20%;
  height: 100px;
  text-align: center;
  border: 1px solid black;
  color: #ffffff;
}
</style>