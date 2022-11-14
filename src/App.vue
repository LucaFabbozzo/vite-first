<script>
import AppTitle from "./components/AppTitle.vue";
import Button from "./components/Button.vue";
import Header from "./components/Header.vue"

export default {
  components: { AppTitle, Button, Header },
  name: "App",
  data() {
    return {
      
    };
  },
};
</script>


<template> 
  <Header />    
  <App-title />
  <Button />
</template>


<style scoped>

</style>