<script>
import AppHeader from './components/AppHeader.vue';
import AppGallery from './components/AppGallery.vue';
export default {
  name: 'Vite Hello World',
  components: {
    AppHeader: AppHeader,
    AppGallery: AppGallery
  }
}
</script>



<template>
  <App-Header></App-Header>
  <App-Gallery></App-Gallery>
</template>



<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>