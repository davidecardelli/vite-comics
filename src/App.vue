<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'


export default {
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
    <div class="container">
        <app-header></app-header>
        <app-main></app-main>
        <app-footer></app-footer>
    </div>
</template>

<style>

</style>