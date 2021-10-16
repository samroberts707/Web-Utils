<template>
    <div class="homepage">
        <div class="header">
          <img class="logo" alt="Web Utils" src="https://via.placeholder.com/150" />
          <h1>Web Utils</h1>
        </div>
        <div class="intro">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse malesuada, justo id finibus sodales, lectus lacus porta ante, sit amet elementum mi est et arcu. Donec sem libero, molestie ut ipsum a, ultricies tincidunt elit. Vestibulum placerat, diam ultrices tincidunt aliquet, quam arcu venenatis tortor, et aliquam magna urna sit amet ante.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse malesuada, justo id finibus sodales, lectus lacus porta ante, sit amet elementum mi est et arcu. Donec sem libero, molestie ut ipsum a, ultricies tincidunt elit. Vestibulum placerat, diam ultrices tincidunt aliquet, quam arcu venenatis tortor, et aliquam magna urna sit amet ante.</p>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Home',
  head: {
    title: 'Web Utils'
  }
}
</script>
<style lang="scss" scoped>
div.homepage {
  display: block;
  position: relative;
  div.header {
    display: grid;
    position: relative;
    align-items: center;
    justify-items: center;
    padding: 50px 0;
    img.logo {
      display: block;
      position: relative;
      margin-bottom: 15px;
    }
    h1 {
      text-align: center;
    }
  }
}
</style>