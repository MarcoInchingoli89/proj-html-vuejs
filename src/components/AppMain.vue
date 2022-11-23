<script>
import SectionOverview from './AppMain/SectionOverview.vue'
import SectionCareer from './AppMain/SectionCareer.vue'
import SectionCourses from './AppMain/SectionCourses.vue'
import SectionTestimonials from './AppMain/SectionTestimonials.vue'
import SectionStaff from './AppMain/SectionStaff.vue'
import SectionBlog from './AppMain/SectionBlog.vue'
export default {
    name: 'AppMain',
    components: {
        SectionOverview,
        SectionCareer,
        SectionCourses,
        SectionTestimonials,
        SectionStaff,
        SectionBlog,
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

    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.title {
    margin-top: 150px;
}

.blog {
    background-color: $dl-primary;

    .row {
        padding-bottom: 3rem;
    }

    .card {
        background-color: $dl-primary;
    }

    .container {
        max-width: 70%;
    }

    .card_body {

        .subtitle {
            font-size: 0.7rem;
        }

        .text {
            font-size: 1rem;
        }

        span {
            font-size: 0.7rem;
        }
    }
}


.green {
    color: $dl-secondary;
}
</style>