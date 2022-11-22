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
                                <img class="img-fluid card-img-top" src="../assets/img/course-02-480x298.jpg" alt="">
                            </div>
                            <div class="card_body">
                                <div class="price text-left p-3 green fw-bold">$40<span>.00</span></div>
                                <h6 class="text text-left px-3 fw-bold">Learning to Write as a Professional Author</h6>
                                <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                    <span class="text-muted fw-bold">20 Lessons</span>
                                    <span class="text-muted fw-bold">50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div style="width: 18rem;"
                            class="card border-0 bg-white d-flex justify-content-center align-items-center">
                            <div class="card_image">
                                <img class="img-fluid card-img-top" src="../assets/img/stock-full-hd-03-480x298.jpg"
                                    alt="">
                            </div>
                            <div class="card_body">
                                <div class="price text-left p-3 green fw-bold">$0<span>.00</span></div>
                                <h6 class="text text-left px-3 fw-bold">Customer-centric Info-Tech Strategies</h6>
                                <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                    <span class="text-muted fw-bold">24 Lessons</span>
                                    <span class="text-muted fw-bold">769 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div style="width: 18rem;"
                            class="card border-0 bg-white d-flex justify-content-center align-items-center">
                            <div class="card_image">
                                <img class="img-fluid card-img-top" src="../assets/img/stock-full-hd-04-480x298.jpg"
                                    alt="">
                            </div>
                            <div class="card_body">
                                <div class="price text-left p-3 green fw-bold">$19<span>.00</span></div>
                                <h6 class="text text-left px-3 fw-bold">Open Programing Courses for Everyone: Python
                                </h6>
                                <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                    <span class="text-muted fw-bold">17 Lessons</span>
                                    <span class="text-muted fw-bold">62 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="circles d-flex gap-3 justify-content-center align-items-center py-4">
                <div class="circle_big rounded-circle"></div>
                <div class="circle rounded-circle"></div>
                <div class="circle rounded-circle"></div>
                <div class="circle rounded-circle"></div>
                <div class="circle rounded-circle"></div>
            </div>
            <div class="disclaimer d-flex flex-column align-items-center">
                <p class="text-muted fw-bold m-0">Control your personal preference settings to get notified about</p>
                <span class="text-muted fw-bold">appropriate
                    courses.<a class="text-decoration-none text-body fw-bold border-bottom border-2 pt-1" href="#">
                        View
                        all
                        courses</a></span>
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

    .circles {
        .circle_big {
            height: 10px;
            width: 10px;
            background-color: black;
        }

        .circle {
            height: 6px;
            width: 6px;
            background-color: lightgrey;
        }
    }

    .disclaimer {
        font-size: 0.8rem;
        padding-bottom: 6rem;
    }
}


.green {
    color: $dl-secondary;
}
</style>