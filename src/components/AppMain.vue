<script>
import SectionOverview from './AppMain/SectionOverview.vue'
import SectionCareer from './AppMain/SectionCareer.vue'
export default {
    name: 'AppMain',
    components: {
        SectionOverview,
        SectionCareer,
    }
}
</script>

<template>

    <main id="site_main">
        <SectionOverview />

        <SectionCareer />

        <section class="courses">
            <div class="title text-center">
                <h6 class="text-uppercase text-secondary">Join Maxcoach at best
                </h6>
                <h2 class="fw-bold">Latest Online <span class="fw-normal green">Courses</span></h2>
            </div>
        </section>

    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container {
    max-width: 70%;
}

.image {
    position: relative;

    .index_0 {
        position: absolute;
        bottom: 0;
        top: 100px;
    }

    .index_1 {
        position: absolute;
        z-index: 1;
        bottom: 35%;
        left: 45%;

        &:hover {
            cursor: pointer;
        }
    }
}

.text {
    margin-top: 150px;
    max-width: 30%;
    padding-left: 4rem;
}

.green {
    color: $dl-secondary;
}

.title {
    margin-top: 150px;
}
</style>