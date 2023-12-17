<script>
import Appheader from './components/Appheader.vue';
import Appmain from './components/Appmain.vue';
import Appfooter from './components/Appfooter.vue';

export default {
  name: 'App',
  components: {
    Appheader,
    Appmain,
    Appfooter
  }
}
</script>

<template lang="">
    <Appheader/>
    <Appmain/>
    <Appfooter/>
</template>

<style lang="scss">
@use './components/style/general.scss' as *;
// @use './components/style/partials/mixins' as *;
</style>

<!-- commands start
Berna@192 vite-comics % cd /Users/Berna/Desktop/vite-comics/vite-comics
Berna@192 vite-comics % npm run dev 
-->