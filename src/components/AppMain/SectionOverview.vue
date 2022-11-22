<script>
export default {
    name: 'SectionOverview',
}
</script>

<template>

    <section class="overview mt-5">
        <div class="container">
            <div class="row row-cols-2 gap-4">
                <!-- Testo sezione overview -->
                <div class="col overview_text">
                    <h6 class="text-uppercase text-secondary">Everything in <span
                            class="text-muted fw-bold">Maxcoach</span>
                    </h6>
                    <h1 class="fw-bold">Learn about our <span class="fw-normal green">Work Culture</span> at
                        MaxCouch</h1>
                    <p class="text-muted">Spend some time to visit our website or head office and discover our
                        current courses,
                        enrollmente procedure, and registration deadline. We're opening new classes every beginning
                        of each month.
                    </p>
                    <p class="text-body">Have questions? <a class="text-decoration-none green fw-bold border-bottom"
                            href="#">Get Free
                            Guide</a></p>
                </div>
                <!-- Immagine sezione overview -->
                <div class="col overview_image">
                    <img class="index_0 img-fluid rounded-1"
                        src="../../assets/img/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
                    <img class="rounded-1 img-fluid index_1" width="150"
                        src="../../assets/img/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
                </div>
            </div>
            <!-- Statistiche sezione overview -->
            <div class="stats_overview d-flex my-4 justify-content-center gap-4">
                <div class="enrolled_learners stats_padding fs-1">
                    <h2 class="text-center green fw-bold">129+</h2>
                    <h6 class="text-uppercase text-muted fw-bold">Enrolled Learners</h6>
                </div>
                <div class="finished_sessions fs-1 stats_padding_y">
                    <h2 class="text-center green fw-bold">80</h2>
                    <h6 class="text-uppercase text-muted fw-bold">Finished Sessions</h6>
                </div>
                <div class="satisfaction_rate stats_padding fs-1">
                    <h2 class="text-center green fw-bold">4%</h2>
                    <h6 class="text-uppercase text-muted fw-bold">Satisfaction Rate</h6>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

.container {
    max-width: 60%;
}

.overview_image {
    position: relative;

    .index_0 {
        position: absolute;
        bottom: 0;
        top: 100px;
    }

    .index_1 {
        position: absolute;
        z-index: 1;
        top: 10%;
        left: 85%;
    }
}

.overview_text {
    margin-top: 100px;
    max-width: 45%;
}

.green {
    color: $dl-secondary;
}

.stats_overview {
    .stats_padding {
        padding: 2rem 4rem;
    }

    .stats_padding_y {
        padding: 2rem 0;
    }
}
</style>