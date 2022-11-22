<script>
import SectionOverview from './AppMain/SectionOverview.vue'
export default {
    name: 'AppMain',
    components: {
        SectionOverview,
    }
}
</script>

<template>

    <main id="site_main">
        <SectionOverview />


    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

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