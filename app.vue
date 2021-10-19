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
  @font-face {
    font-family: Meedori-Sans;
    src: url('/assets/fonts/Meedori-Sans/Meedori-Sans-Regular.ttf');
  }
  :root {
    --text-black: #626262;
    --grey: #d1d1d1;
    --blue-sapphire: #28536b;
    --cyan: #65f6e9;
    --light-salmon: #f7a278;
    --bright-maroon: #ba324f;
    --princeton-orange: #e77728;
  }
  /* width */
  ::-webkit-scrollbar {
    width: 13px;
  }

  /* Track */
  ::-webkit-scrollbar-track {
    background: #FFFFFF;
  }

  /* Handle */
  ::-webkit-scrollbar-thumb {
    background: var(--blue-sapphire);
    border: 2px solid #FFFFFF;
    border-radius: 20px;
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
      div.component {
        div.header {
          display: grid;
          position: relative;
          align-items: center;
          justify-items: center;
          padding: 50px 0;
        }
        label {
          display: block;
          position: relative;
        }
        textarea {
          display: block;
          position: relative;
          width: 100%;
          border: 2px solid var(--grey);
          border-radius: 5px;
          outline: none;
        }
        button {
          display: block;
          position: relative;
          margin: 10px 0;
          background-color: #FFFFFF;
          border: 2px solid var(--grey);
          padding: 8px 21px;
          cursor: pointer;
          transition: border 0.3s ease-in-out, color 0.3s ease-in-out;
          &.cyan {
            &:hover {
              color: var(--cyan);
              border-color: var(--cyan);
            }
          }
        }
      }
    }
    h1, h2, h3, h4, h5, h6, p, a, li, span, button, label, textarea {
      font-family: 'Nunito', sans-serif;
      margin: 0;
      color: var(--text-black);
      &.brand {
        font-family: 'Meedori-Sans', 'Nunito', sans-serif;
      }
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
    p, li, a, button, textarea {
      font-size: 20px;
      line-height: 24px;
      margin-bottom: 10px;
      font-weight: 200;
    }
    label {
      font-size: 16px;
      line-height: 20px;
      font-weight: 200;
    }
  }
</style>