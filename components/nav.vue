<template>
    <nav>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        <div class="nav-item top">
            <router-link to="/">Home</router-link>
        </div>
        
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
        div.nav-item {
            display: block;
            position: relative;
            padding: 20px 40px;
        }
        a {
            position: relative;
            font-family: 'Rubik', 'Nunito', sans-serif;
            font-size: 22px;
            line-height: 26px;
            text-decoration: none;
            &::after {
                content: '';
                display: block;
                position: absolute;
                width: 0;
                height: 2px;
                bottom: 1px;
                left: 0;
                background-color: var(--keppel);
                border-radius: 10px;
                transition: width 0.5s cubic-bezier(0.075, 0.82, 0.165, 1);
            }
            &:hover::after {
                width: 100%;
            }
        }
    }
</style>
// Inspiration:
// https://www.evozyne.com/
// https://gagehotel.com/