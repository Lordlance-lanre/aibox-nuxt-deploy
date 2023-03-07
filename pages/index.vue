<template>
 <div class="bg-indigo-600 pt-20 md:w-screen  h-screen">
  <div id="top" class="text-center text-white text-6xl font-medium tracking-wide">
    tutu
  </div>
  <div class="text-center text-white mt-3 font-light tracking-wide">
    <p>Welcome to tutu-wallets for all</p>
  </div>

  <div>
    <LoginInfo/>
  </div>
 </div>
</template>

<script setup>
import { ref } from '@nuxtjs/composition-api';
import LoginInfo from '../components/LoginInfo.vue'

const newPage = ref('Yes');
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap');
#top{
  font-family: Fredoka One;
}
</style>
