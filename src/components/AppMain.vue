<script>
import HeroMain from './main-components/HeroMain.vue';
import OnlineCorses from './main-components/OnlineCorses.vue';
import Tutoring from './main-components/Tutoring.vue';
export default {
    name: "AppMain",
    components: { HeroMain, OnlineCorses, Tutoring }
}
</script>

<template>
    <main>
        <HeroMain />
        <OnlineCorses />
        <Tutoring />
    </main>
</template>

<style lang="scss" scoped>

</style>