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
        background-color: red;
        top: 0;
        left: 0;
        z-index: 10;
    }
</style>