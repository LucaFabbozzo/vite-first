<script>
export default {
  name: "Button",
  data() {
    return {
      send: "inizia il viaggio",
    };
  },
};
</script>

<template>
  <div class="btn">
    <a href="#">{{ send }}</a>
  </div>
</template>

<style scoped>
.btn {
  background-color: #e6e6e6;
  padding: 10px 15px;
  border-radius: 5px;
  width: 150px;
  margin:  auto;
  text-align: center;
  border: 1px solid #c8c8c8;
  box-shadow: 1px 2px 1px  rgba(0, 0, 0, 0.1);
  cursor: pointer;
}

.btn a {
  text-decoration: none;
  color: #141414;
}

.btn:hover {
  background-color: #c9c9c9;
}
</style>
