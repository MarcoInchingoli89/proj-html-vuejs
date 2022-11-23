<script>
export default {
    name: 'SiteHeader',
}
</script>

<template>
    <header id="site_header">
        <!-- Navbar -->
        <nav class="navbar d-flex justify-content-around">
            <div class="left_menu">
                <ul class="d-flex gap-5 p-0 mb-0">
                    <a href="#">
                        <li>Home</li>
                    </a>
                    <a href="#">
                        <li>Pages</li>
                    </a>
                    <a href="#">
                        <li>Courses</li>
                    </a>
                    <a href="#">
                        <li>Features</li>
                    </a>
                    <a href="#">
                        <li>Blog</li>
                    </a>
                    <a href="#">
                        <li>Shop</li>
                    </a>
                </ul>
            </div>
            <div class="logo d-flex">
                <img width="150" src="../assets/img/dark-logo.png" alt="">
            </div>
            <div class="right_menu">
                <input class="search_bar rounded-1 py-2 border-0" type="search" placeholder="Search">
            </div>
        </nav>
        <!-- Jumbotron -->
        <div class="jumbotron d-flex justify-content-center align-items-center flex-column">
            <h5 class="text-white fw-bold">Commence Business</h5>
            <h1 class="text-white fw-light">Distant Monitoring Program</h1>
            <a class="btn text-decoration-none p-2" href="#" role="button">Download free guidebook</a>
            <div class="sidebar rounded-1"></div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.navbar {

    a {
        text-decoration: none;
        color: black;
        font-size: 0.8rem;
    }

    li {
        list-style: none;
    }

    .logo {
        width: 500px;
    }

    .search_bar {
        width: 250px;
        background-color: #f5f5f5;
    }
}

.jumbotron {
    background-image: url('../assets/img/home-3-hero-bg.jpg');
    background-size: cover;
    height: 550px;
    position: relative;

    a {
        background-color: white;
    }

    a:hover {
        background-color: $dl-secondary_dark;
        color: white;
    }

    .btn {
        color: $dl-secondary;
        font-size: 0.7rem;
        font-weight: bold;

        &hover {
            background-color: $dl-secondary_dark;
        }
    }

}

.sidebar {
    height: 125px;
    width: 35px;
    background-color: white;
    position: absolute;
    right: 0;
    top: 20%;
}
</style>