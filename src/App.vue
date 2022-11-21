<script>
import AppHeader from './components/AppHeader.vue'
export default {
  name: 'App',
  components: {
    AppHeader,
  }
}
</script>

<template>
  <AppHeader />

  <main id="site_main">
    <section class="overview">
      <div class="container">
        <div class="row row-cols-2">
          <div class="col overview_text">
            <h6>Everything in <span>Maxcoach</span></h6>
            <h2>Learn about our <span>Work Culture</span> at MaxCouch</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, eligendi? Minima optio amet aut,
              excepturi quibusdam vero ab voluptatibus in et eligendi ipsum voluptate, sapiente architecto facere autem
              quod pariatur.</p>
            <p>Have questions? <a class="text-decoration-none" href="#">Get Free Guide</a></p>
          </div>
          <div class="col overview_image rounded-1">
            <img class="rounded-1" width="150"
              src="./assets/img/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
          </div>
        </div>
        <div class="stats_overview d-flex my-4 justify-content-center gap-4">
          <div class="enrolled_learners stats_padding fs-1">
            <h2 class="text-center">129+</h2>
            <h5>Enrolled Learners</h5>
          </div>
          <div class="finished_sessions fs-1 stats_padding_y">
            <h2 class="text-center">80</h2>
            <h5>Finished Sessions</h5>
          </div>
          <div class="satisfaction_rate stats_padding fs-1">
            <h2 class="text-center">4%</h2>
            <h5>Satisfaction Rate</h5>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<style lang="scss" scoped>
.container {
  max-width: 60%;
}

.overview_image {
  background-image: url('./assets/img/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg');
  background-size: cover;
  margin-top: 150px;
  height: 300px;
  position: relative;

  img {
    position: absolute;
    left: 83%;
    bottom: 70%;
  }
}

.overview_text {
  margin-top: 150px;
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

<!-- TODO -->
<!-- Inizia con l'header OK -->
<!-- Dividi in componenti -->
<!-- Crea un file con le variabili OK -->
<!-- Inserisci il font corretto -->
<!-- Inserisci le icone mancanti -->