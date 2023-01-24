<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'


export default {
    name: 'Dc Comics',
    data() {
        return {

        }
    },
    components: {
        AppHeader,
        AppMain,
        AppFooter
    },
}
</script>

<template>
    <app-header></app-header>
    <app-main></app-main>
    <app-footer></app-footer>
</template>

<style>
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Generics */
body {
    /* font-family: ; */
    min-height: 100vh;
}

img {
    max-width: 100%;
    height: auto;
}

a {
    text-decoration: none;
}

ul {
    list-style-type: none;
}

/* Container */
.container {
    margin: 0 auto;
    max-width: 1140px;
}
</style>