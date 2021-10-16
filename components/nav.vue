<template>
    <nav>
        <router-link to="/">Home</router-link>
    </nav>
</template>
<script>
export default {
    name: 'Navigation',
}
</script>
<style lang="scss" scoped>
    nav {
        display: block;
        position: fixed;
        width: 400px;
        height: 100vh;
        background-color: #FFFFFF;
        border-right: 1px solid #CCCCCC;
        top: 0;
        left: 0;
        z-index: 10;
        overflow: hidden scroll;
        a, p, li {
            display: block;
            position: relative;
            font-family: 'Rubik', 'Nunito', sans-serif;
            font-size: 22px;
            line-height: 26px;
            text-decoration: none;
            padding: 20px 40px;
        }
    }
</style>
// Inspiration:
// https://www.evozyne.com/
// https://gagehotel.com/