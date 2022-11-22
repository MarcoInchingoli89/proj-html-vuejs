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