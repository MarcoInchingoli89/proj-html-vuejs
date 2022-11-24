<script>
import SectionOverview from './appmain/SectionOverview.vue'
import SectionCareer from './appmain/SectionCareer.vue'
import SectionCourses from './appmain/SectionCourses.vue'
import SectionTestimonials from './appmain/SectionTestimonials.vue'
import SectionStaff from './appmain/SectionStaff.vue'
import SectionBlog from './appmain/SectionBlog.vue'
import SectionNewsletter from './appmain/SectionNewsletter.vue'
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