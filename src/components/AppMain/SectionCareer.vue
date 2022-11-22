<script>
export default {
    name: 'SectionCareer',
}
</script>

<template>

    <section class="career">
        <div class="container">
            <div class="row row-cols-2 gap-4">
                <!-- Immagine sezione career -->
                <div class="col image">
                    <img class="index_0 img-fluid rounded-1 shadow-lg"
                        src="../../assets/img/stock-full-hd-11-670x450.jpg" alt="">
                    <img class="rounded-1 img-fluid index_1" width="70" src="../../assets/img/icon-youtube-play.png"
                        alt="">
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

</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

.container {
    max-width: 70%;
}

.image {
    position: relative;

    .index_0 {
        position: absolute;
        bottom: 0;
        top: 100px;
    }

    .index_1 {
        position: absolute;
        z-index: 1;
        bottom: 35%;
        left: 45%;

        &:hover {
            cursor: pointer;
        }
    }
}

.text {
    margin-top: 150px;
    max-width: 30%;
    padding-left: 4rem;
}

.green {
    color: $dl-secondary;
}
</style>