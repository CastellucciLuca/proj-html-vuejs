<script>
import HeroMain from './main-components/HeroMain.vue';
import OnlineCorses from './main-components/OnlineCorses.vue';
import Tutoring from './main-components/Tutoring.vue';
import TopLearners from './main-components/TopLearners.vue';
import BestBlog from './main-components/BestBlog.vue';
import Newsletter from './main-components/Newsletter.vue';
export default {
    name: "AppMain",
    components: { HeroMain, OnlineCorses, Tutoring, TopLearners, BestBlog, Newsletter}
}
</script>

<template>
    <main>
        <HeroMain />
        <OnlineCorses />
        <Tutoring />
        <TopLearners  class="bg-red"/>
        <BestBlog class="bg-red"/>
        <Newsletter />
    </main>
</template>

<style lang="scss" scoped>

</style>