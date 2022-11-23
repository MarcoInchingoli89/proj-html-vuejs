<script>
import SectionOverview from './AppMain/SectionOverview.vue'
import SectionCareer from './AppMain/SectionCareer.vue'
import SectionCourses from './AppMain/SectionCourses.vue'
import SectionTestimonials from './AppMain/SectionTestimonials.vue'
import SectionStaff from './AppMain/SectionStaff.vue'
export default {
    name: 'AppMain',
    components: {
        SectionOverview,
        SectionCareer,
        SectionCourses,
        SectionTestimonials,
        SectionStaff
    }
}
</script>

<template>

    <main id="site_main">
        <SectionOverview />

        <SectionCareer />

        <SectionCourses />

        <SectionTestimonials />

        <SectionStaff />

    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container {
    max-width: 70%;
}

.text {
    margin-top: 250px;
    max-width: 35%;
}

.image {
    margin-top: 150px;
}

.btn {
    background-color: $dl-secondary;
    width: 135px;
    font-size: 0.6rem;
    font-weight: bold;
}


.green {
    color: $dl-secondary;
}
</style>