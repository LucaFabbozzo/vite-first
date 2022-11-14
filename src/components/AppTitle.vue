<script>
export default {
  name: 'AppTitle',
  data() {
    return {
      title: 'La mia prima app con Vite!'
    }
  }
}
</script>


<template>
  <div class="container">
    <h2>{{title}}</h2>
  </div>
</template>


<style>
  h2 {
    color: #272727;
    text-transform: uppercase;
  }
  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 100px auto;
    width: 50%;
    height: 300px;
    text-align: center;
    background-color: #f2f2f2;
    border: 1px solid black;
  }
</style>