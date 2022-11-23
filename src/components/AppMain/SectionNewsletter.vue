<script>
export default {
    name: 'SectionNewsletter',
}
</script>

<template>

    <section class="newsletter">
        <!-- titolo -->
        <div class="title text-center pt-2 pb-2">
            <h2 class="fw-bold">Subscribe <span class="fw-normal green">Newsletter</span></h2>
        </div>
        <!-- testo -->
        <div class="disclaimer d-flex flex-column align-items-center">
            <p class="text-muted fw-bold m-0">Enter your email address to register to our newsletter subscription
            </p>
            <span class="text-muted fw-bold">delivered on a regular basis!</span>
            <!-- input newsletter -->
            <div class="newsletter_input d-flex justify-content-center">
                <input type="email" class="form-control text border-0 rounded-0 rounded-start" id="exampleInputEmail1"
                    aria-describedby="emailHelp" placeholder="Enter your email">
                <button type="submit" class="btn green_bg fw-bold text-white rounded-0 rounded-end">Subscribe</button>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

.title {
    margin-top: 40px;
}

.disclaimer {
    font-size: 0.8rem;
    padding-bottom: 2rem;
}

.newsletter_input {
    width: 50%;

    input {
        background-color: $dl-primary;
        margin-top: 1rem;
        width: 50%;
    }

    .text {
        font-size: 0.7rem;
        height: 2.4rem;
    }

    button {
        font-size: 0.6rem;
        padding: 0.7rem 1.2rem;
        height: 38px;
        margin-top: 1rem;
    }

}

.green {
    color: $dl-secondary;
}

.green_bg {
    background-color: $dl-secondary_dark;
}
</style>