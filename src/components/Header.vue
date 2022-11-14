<script>

export default {
  name: 'Header',
  data() {
    return {
      logo: 'src/assets/img/logo.png'
    }
  }
};

</script>

<template>
  <header>
    <div class="logo">
      <img :src="logo" alt="">
    </div>
    <nav>
      <ul>
        <li>Inizia</li>
        <li>Perchè Vite</li>
        <li>Docs</li>
        <li>Vite</li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
  .logo img{
    width: 60px;
  }

  header {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    background-color: #efefef;
    box-shadow: 1px 2px 1px  rgba(0, 0, 0, 0.1);
  }

  header nav ul {
    width: 500px;
    display: flex;
    justify-content: space-between;
  }

  header nav ul li {
    list-style: none;
    cursor: pointer;
  }

   header nav ul li:hover {
    color: #525252;
   }
</style>
