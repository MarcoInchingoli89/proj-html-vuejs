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
            <div class="title text-center pt-3 pb-5">
                <h6 class="text-uppercase text-muted fw-bold">Join Maxcoach at best
                </h6>
                <h2 class="fw-bold">Latest Online <span class="fw-normal green">Courses</span></h2>
            </div>
            <div class="container">
                <div class="row row-cols-3">
                    <div class="col">
                        <div style="width: 18rem;"
                            class="card border-0 bg-white d-flex justify-content-center align-items-center">
                            <div class="card_image">
                                <img class="img-fluid card-img-top" width="250"
                                    src="../assets/img/course-02-480x298.jpg" alt="">
                            </div>
                            <div class="card_body">
                                <div class="price text-left p-3 green fw-bold">$40<span>.00</span></div>
                                <h6 class="text text-left px-3 fw-bold">Learning to Write as a Professional Author</h6>
                                <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                    <span>20 Lessons</span>
                                    <span>50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div style="width: 18rem;"
                            class="card border-0 bg-white d-flex justify-content-center align-items-center">
                            <div class="card_image">
                                <img class="img-fluid card-img-top" width="250"
                                    src="../assets/img/course-02-480x298.jpg" alt="">
                            </div>
                            <div class="card_body">
                                <div class="price text-left p-3 green fw-bold">$40<span>.00</span></div>
                                <h6 class="text text-left px-3 fw-bold">Learning to Write as a Professional Author</h6>
                                <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                    <span>20 Lessons</span>
                                    <span>50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div style="width: 18rem;"
                            class="card border-0 bg-white d-flex justify-content-center align-items-center">
                            <div class="card_image">
                                <img class="img-fluid card-img-top" width="250"
                                    src="../assets/img/course-02-480x298.jpg" alt="">
                            </div>
                            <div class="card_body">
                                <div class="price text-left p-3 green fw-bold">$40<span>.00</span></div>
                                <h6 class="text text-left px-3 fw-bold">Learning to Write as a Professional Author</h6>
                                <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                    <span>20 Lessons</span>
                                    <span>50 Students</span>
                                </div>
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

.title {
    margin-top: 150px;
}

.courses {
    background-color: $dl-primary;

    .container {
        max-width: 70%;
    }

    .card_body {

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