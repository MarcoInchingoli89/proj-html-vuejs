<script>
export default {
    name: 'SectionBlog',
}
</script>

<template>

    <section class="blog">
        <div class="title text-center pt-3 pb-5">
            <h6 class="text-uppercase text-muted fw-bold">Read for more joyment
            </h6>
            <h2 class="fw-bold">Latest From <span class="fw-normal green">Our Blogs</span></h2>
        </div>
        <div class="container">
            <div class="row row-cols-3">
                <!-- cards -->
                <div class="col">
                    <div style="width: 18rem;" class="card border-0 d-flex justify-content-center align-items-center">
                        <div class="card_image">
                            <img class="img-fluid card-img-top" src="../../assets/img/artist-blog-03-480x325.jpeg"
                                alt="">
                        </div>
                        <div class="card_body">
                            <div class="subtitle text-left p-3 fw-bold text-muted text-uppercase">Artist</div>
                            <h6 class="text text-left px-3 fw-bold">Brush Strokes Energize Trees in Painting</h6>
                            <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                <span class="text-muted fw-bold">May 15, 2020</span>
                                <span class="text-muted fw-bold">688 views</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div style="width: 18rem;" class="card border-0 d-flex justify-content-center align-items-center">
                        <div class="card_image">
                            <img class="img-fluid card-img-top" src="../../assets/img/artist-blog-01-480x325.jpg"
                                alt="">
                        </div>
                        <div class="card_body">
                            <div class="subtitle text-left p-3 fw-bold text-muted text-uppercase">Artist</div>
                            <h6 class="text text-left px-3 fw-bold">Pocket-Sized Notebooks Hold Miniature Paintings
                            </h6>
                            <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                <span class="text-muted fw-bold">May 15, 2020</span>
                                <span class="text-muted fw-bold">603 views</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div style="width: 18rem;" class="card border-0 d-flex justify-content-center align-items-center">
                        <div class="card_image">
                            <img class="img-fluid card-img-top" src="../../assets/img/artist-blog-02-480x325.jpg"
                                alt="">
                        </div>
                        <div class="card_body">
                            <div class="subtitle text-left p-3 fw-bold text-muted text-uppercase">Artist</div>
                            <h6 class="text text-left px-3 fw-bold">Connection Between Self-Portraits and Identity
                            </h6>
                            <div class="statistics text-center py-3 px-3 d-flex gap-3 justify-content-start">
                                <span class="text-muted fw-bold">May 15, 2020</span>
                                <span class="text-muted fw-bold">397 views</span>
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