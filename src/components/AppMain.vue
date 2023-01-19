<script>
import HeroMain from './main-components/HeroMain.vue';
import OnlineCorses from './main-components/OnlineCorses.vue';
import Tutoring from './main-components/Tutoring.vue';
import TopLearners from './main-components/TopLearners.vue';
export default {
    name: "AppMain",
    components: { HeroMain, OnlineCorses, Tutoring, TopLearners }
}
</script>

<template>
    <main>
        <HeroMain />
        <OnlineCorses />
        <Tutoring />
        <TopLearners  class="top-learners"/>
    </main>
</template>

<style lang="scss" scoped>

</style>