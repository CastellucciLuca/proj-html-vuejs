<script>
import HeroMain from './main-components/HeroMain.vue';
import OnlineCorses from './main-components/OnlineCorses.vue';
export default {
    name: "AppMain",
    components: { HeroMain, OnlineCorses }
}
</script>

<template>
    <main>
        <HeroMain />
        <OnlineCorses />
    </main>
</template>

<style lang="scss" scoped>

</style>