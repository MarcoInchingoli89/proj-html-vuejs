<script>
export default {
  name: 'App',
}
</script>

<template>
  <header id="site_header">
    <nav class="navbar d-flex justify-content-around">
      <div class="left_menu">
        <ul class="d-flex gap-5 p-0 mb-0">
          <li>Courses</li>
          <li>Features</li>
          <li>Blog</li>
          <li>Shop</li>
        </ul>
      </div>
      <div class="logo d-flex">
        <img width="150" src="./assets/img/dark-logo.png" alt="">
      </div>
      <div class="right_menu">
        <input class="search_bar rounded-1 py-2" type="search" placeholder="Search">
      </div>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
li {
  list-style: none;
}

.logo {
  width: 500px;
}

.search_bar {
  width: 250px;
}
</style>

<!-- TODO -->
<!-- Inizia con l'header -->
<!-- Dividi in componenti -->
<!-- Crea un file con le variabili -->