<script>
import AppTitle from './AppTitle.vue';
  export default {
    name: 'AppJumbo',
    components:{
        AppTitle
    }

  }
</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
  </div>
</template>

<style scoped>
.container{
    width: 100%;
    height: 400px;
    background-image: url(https://www.serverplan.com/blog/wp-content/uploads/2022/07/colore-google.jpg);
    background-size: cover;
    background-position: center;
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>