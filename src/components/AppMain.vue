<script>
import SectionOverview from './AppMain/SectionOverview.vue'
import SectionCareer from './AppMain/SectionCareer.vue'
import SectionCourses from './AppMain/SectionCourses.vue'
export default {
    name: 'AppMain',
    components: {
        SectionOverview,
        SectionCareer,
        SectionCourses,
    }
}
</script>

<template>

    <main id="site_main">
        <SectionOverview />

        <SectionCareer />

        <SectionCourses />

        <section class="testimonials">
            <div class="container">
                <div class="row row-cols-2 gap-4">
                    <!-- Testo sezione testimonials -->
                    <div class="col text">
                        <h6 class="text-uppercase text-muted fw-bold">Testimonials
                        </h6>
                        <h2 class="fw-bold">Why Do People <span class="fw-normal green">*Hearts*</span> Us
                        </h2>
                        <p class="text-muted">Seeking for verbals of our service quality? Find them here. Everything is
                            transparent and straightforward for your sense of justification.
                        </p>
                        <p><a class="text-decoration-none fw-bold border-bottom border-2 text-body" href="#">View
                                all</a></p>
                    </div>
                    <!-- Card sovrapposte -->
                    <div class="col cards">
                        <div class="card bg-white" style="width: 18rem;">
                            <div class="card-body">
                                <h6 class="card-title">Card title</h6>
                                <p class="card-subtitle mb-2 text-muted">Card subtitle</p>
                            </div>
                        </div>
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