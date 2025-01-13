<template>
  <Home/>
</template>

<script>
import Home from '@/components/home/Home.vue';

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app {
  display: flex;
  justify-content: center;
  width: 100%;
  height: 100%;
}
</style>
