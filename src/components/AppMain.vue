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

        <section class="newsletter">
            <div class="title text-center pt-2 pb-2">
                <h2 class="fw-bold">Subscribe <span class="fw-normal green">Newsletter</span></h2>
            </div>
            <div class="disclaimer d-flex flex-column align-items-center">
                <p class="text-muted fw-bold m-0">Enter your email address to register to our newsletter subscription
                </p>
                <span class="text-muted fw-bold">delivered on a regular basis!</span>
                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                <button type="submit" class="btn btn-primary">Submit</button>
            </div>
        </section>
    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.title {
    margin-top: 40px;
}

.disclaimer {
    font-size: 0.8rem;
    padding-bottom: 2rem;
}

.green {
    color: $dl-secondary;
}
</style>