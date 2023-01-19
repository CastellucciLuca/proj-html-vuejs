<script setup>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue'
</script>

<template>
    <!-- Import Header -->
    <AppHeader class="shadow-sm" />
    <!-- Import Main -->
    <AppMain />
    <!-- Import Footer -->
    <AppFooter />
</template>

<style lang="scss">
@use 'bootstrap/scss/bootstrap.scss' as *;
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
</style>
