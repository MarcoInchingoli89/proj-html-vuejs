<script>
import SectionOverview from './AppMain/SectionOverview.vue'
import SectionCareer from './AppMain/SectionCareer.vue'
import SectionCourses from './AppMain/SectionCourses.vue'
import SectionTestimonials from './appmain/SectionTestimonials.vue'
import SectionStaff from './AppMain/SectionStaff.vue'
import SectionBlog from './AppMain/SectionBlog.vue'
import SectionNewsletter from './AppMain/SectionNewsletter.vue'
export default {
    name: 'SiteMain',
    components: {
        SectionOverview,
        SectionCareer,
        SectionCourses,
        SectionTestimonials,
        SectionStaff,
        SectionBlog,
        SectionNewsletter
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

        <SectionBlog />

        <SectionNewsletter />

    </main>
</template>

<style lang="scss" scoped>

</style>