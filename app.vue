<template>
  <div class="app">
    <Navigation />
    <div class="page">
      <NuxtPage/>
    </div>
    
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
<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200;0,300;1,200;1,300&family=Rubik:ital,wght@0,300;0,400;1,300;1,400&display=swap');
  :root {
    --text-black: #626262;
    --blue-sapphire: #28536b;
    --keppel: #58b09c;
    --light-salmon: #f7a278;
    --bright-maroon: #ba324f;
    --princeton-orange: #e77728;
  }
  .app {
    display: block;
    position: relative;
    padding-left: 400px;
    div.page {
      display: block;
      position: relative;
      padding: 0 75px;
      margin: 0 auto;
      max-width: 1200px;
    }
    h1, h2, h3, h4, h5, h6, p, a, li, span, button {
      font-family: 'Nunito', sans-serif;
      margin: 0;
      color: var(--text-black);
    }
    h1 {
      font-size: 40px;
      line-height: 44px;
      font-weight: 300;
    }
    h2 {
      font-size: 32px;
      line-height: 36px;
      font-weight: 300;
    }
    h3 {
      font-size: 28px;
      line-height: 34px;
      font-weight: 300;
    }
    p {
      font-size: 20px;
      line-height: 24px;
      margin-bottom: 10px;
      font-weight: 200;
    }
  }
</style>