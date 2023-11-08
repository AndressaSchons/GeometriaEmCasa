<template>
  <div class="full">
    <div class="wrapper">
    
      <HomeViewVue />
     
    </div>
 
  <RouterView />
  </div>
    
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
import HomeViewVue from './views/HomeView.vue';

</script>

<style scoped>
a{
  text-decoration: none;
}
.full{
  background-image: url(./components/images/background.jpg);
  background-size: cover;
  width: max-content;
  height: max-content;
}
</style>
