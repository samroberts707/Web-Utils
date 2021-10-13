<template>
  <div class="page">
    <Navigation />
    <NuxtPage/>
  </div>
</template>
<script>
import Navigation from './components/nav.vue';
export default {
  components: {
    Navigation,
  }
}
</script>
<style lang="scss" scoped>
  div.page {
    display: block;
    position: relative;
    padding-left: 400px;
  }
</style>