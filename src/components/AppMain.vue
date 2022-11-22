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
                    <!-- Immagine sezione career -->
                    <div class="col image">
                        <img class="index_0 img-fluid rounded-1 shadow-lg"
                            src="../assets/img/home-3-team-image-300x278.png" alt="">
                    </div>
                    <!-- Testo sezione career -->
                    <div class="col text">
                        <h6 class="text-uppercase text-muted fw-bold">How we work
                        </h6>
                        <h2 class="fw-bold">Upgrade Your Skills <span class="fw-normal green">Upgrade Your Life</span>
                        </h2>
                        <p class="text-muted">Opening up more opprtunities in front of you to get the ticket to more
                            enjoyable door in life. Getting equipped with new skills for new sets of insights into your
                            career. MaxCouch accompany learners in every stage of learning.
                        </p>
                        <p><a class="text-decoration-none text-body fw-bold border-bottom border-2" href="#">Download
                                free
                                guidebook</a></p>
                    </div>
                </div>
            </div>
        </section>

    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.text {
    margin-top: 200px;
    max-width: 35%;
}

.cards {
    margin-top: 200px;
}

.container {
    max-width: 70%;
}


.green {
    color: $dl-secondary;
}
</style>