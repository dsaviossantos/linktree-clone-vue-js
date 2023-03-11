<script setup>
import Background from './components/Background.vue'
import MainFace from './components/MainFace.vue'
</script>

<template>
  <Background/>
  <MainFace/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Azeret+Mono:ital,wght@0,400;0,600;0,900;1,400;1,600;1,900&display=swap');
#app {
  font-family: 'Azeret Mono', monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>