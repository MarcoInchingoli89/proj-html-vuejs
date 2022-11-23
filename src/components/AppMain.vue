<script>
import SectionOverview from './AppMain/SectionOverview.vue'
import SectionCareer from './AppMain/SectionCareer.vue'
import SectionCourses from './AppMain/SectionCourses.vue'
import SectionTestimonials from './AppMain/SectionTestimonials.vue'
export default {
    name: 'AppMain',
    components: {
        SectionOverview,
        SectionCareer,
        SectionCourses,
        SectionTestimonials
    }
}
</script>

<template>

    <main id="site_main">
        <SectionOverview />

        <SectionCareer />

        <SectionCourses />

        <SectionTestimonials />

        <section class="staff">
            <div class="container">
                <div class="row row-cols-2 gap-4">
                    <!-- Immagine -->
                    <div class="col image pb-2 ps-5">
                        <img width="380" class="img-fluid rounded-1" src="../assets/img/home-3-team-image.png" alt="">
                    </div>
                    <!-- Testo -->
                    <div class="col text">
                        <h6 class="text-uppercase text-muted fw-bold">Everything in <span
                                class="text-body">Maxcoach</span>
                        </h6>
                        <h2 class="fw-bold">We're Here to <span class="fw-normal green">Transform</span> You!
                        </h2>
                        <p class="text-muted">As learners, people can enjoy great companionship from MaxCoach mentors
                            and educators. We can help you develop and grow at your best.
                        </p>
                        <a class="btn text-decoration-none text-white p-2" href="#" role="button">Get Free Guide</a>
                    </div>
                </div>
            </div>
        </section>

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