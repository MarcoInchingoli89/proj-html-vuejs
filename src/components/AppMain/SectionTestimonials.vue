<script>
export default {
    name: 'SectionTestimonials',
}
</script>

<template>

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
                    <div class="card bg-white shadow border-0" style="width: 30rem;">
                        <div class="card-body">
                            <h6 class="card_title fw-bold">Professional team of spiacialists and passionate mentors at
                                reach
                            </h6>
                            <p class="card-subtitle pt-2 text-muted fw-bold">I need to get a certification for English
                                proficiency and MaxCoach is my best choice. Their tutors are smart and professional when
                                dealing with students.</p>
                            <div class="testimonial d-flex align-items-center">
                                <div class="avatar mt-5 ps-2 mb-2">
                                    <img width="60" class="rounded-circle"
                                        src="../../assets/img/testimonial-avata-01.jpg" alt="">
                                </div>
                                <div class="text">
                                    <h6 class="name fw-bold text-uppercase">
                                        Madley Pondor
                                    </h6>
                                    <p class="job">/ IT Specialist</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card hidden_card_up bg-white shadow border-0" style="width: 30rem;">
                        <div class="card-body">
                            <h6 class="card_title fw-bold">The MaxCoach team works really hard to ensure high level of
                                quality
                            </h6>
                            <p class="card-subtitle pt-2 text-muted fw-bold">I am happy with their arrangement of
                                lessons and subjects. They tutors are smart and professional when
                                dealing with students.</p>
                            <div class="testimonial d-flex align-items-center">
                                <div class="avatar mt-5 ps-2 mb-2">
                                    <img width="60" class="rounded-circle"
                                        src="../../assets/img/testimonial-avata-01.jpg" alt="">
                                </div>
                                <div class="text">
                                    <h6 class="name fw-bold text-uppercase">
                                        Madley Pondor
                                    </h6>
                                    <p class="job">/ IT Specialist</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card hidden_card_down bg-white shadow border-0" style="width: 30rem;">
                        <div class="card-body">
                            <h6 class="card_title fw-bold">Professional team of spiacialists and passionate mentors at
                                reach
                            </h6>
                            <p class="card-subtitle pt-2 text-muted fw-bold">I need to get a certification for English
                                proficiency and MaxCoach is my best choice. Their tutors are smart and professional when
                                dealing with students.</p>
                            <div class="testimonial d-flex align-items-center">
                                <div class="avatar mt-5 ps-2 mb-2">
                                    <img width="60" class="rounded-circle"
                                        src="../../assets/img/testimonial-avata-02.jpg" alt="">
                                </div>
                                <div class="text">
                                    <h6 class="name fw-bold text-uppercase">
                                        Mina Hollace
                                    </h6>
                                    <p class="job">/ Freelancer</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

.text {
    margin-top: 70px;
    max-width: 35%;
}

.row {
    margin-top: 150px;
    align-items: center;
}

.cards {

    position: relative;

    .card {
        height: 250px;
        z-index: 1;
    }

    .hidden_card_up {
        position: absolute;
        z-index: 0;
        bottom: 90px;
        opacity: 0.5;
    }

    .hidden_card_down {
        position: absolute;
        z-index: 0;
        top: 90px;
        opacity: 0.5;
    }

    .card_title {
        font-size: 0.9rem;
    }

    .name {
        font-size: 0.7rem;
        padding-left: 1rem;
    }

    .job {
        font-size: 0.7rem;
        padding-left: 1rem;
    }
}

.container {
    max-width: 70%;
}


.green {
    color: $dl-secondary;
}
</style>