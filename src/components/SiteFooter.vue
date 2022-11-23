<script>
export default {
    name: 'SiteFooter',
}
</script>

<template>

    <footer id="site_footer">
        <div class="container">
            <div class="row row-cols-2">
                <!-- contenuti -->
                <div class="col">
                    <h6 class="text-white fw-bold">Address</h6>
                    <ul>
                        <li><a href="#">382 NE 191st St # 87394 Miami, FL 33179-3899</a></li>
                        <li><a href="#">+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)</a></li>
                        <li><a href="#">support@maxcoach.com</a></li>
                    </ul>
                    <div class="social_media"></div>
                </div>
                <div class="col d-flex">
                    <div class="col">
                        <h6 class="text-white fw-bold">Explore</h6>
                        <ul>
                            <li><a href="#">Start here</a></li>
                            <li><a href="#">Blog</a></li>
                            <li><a href="#">About us</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h6 class="hidden">Placeholder</h6>
                        <ul>
                            <li><a href="#">Success story</a></li>
                            <li><a href="#">Courses</a></li>
                            <li><a href="#">Contact us</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h6 class="text-white fw-bold">Information</h6>
                        <ul>
                            <li><a href="#">Membership</a></li>
                            <li><a href="#">Purchase guide</a></li>
                            <li><a href="#">Privacy policy</a></li>
                            <li><a href="#">Terms of service</a></li>
                        </ul>
                    </div>
                </div>
                <!-- copyright -->
                <div class="copyright d-flex justify-content-center">
                    <p>&#169;2020 Maxcoach, All Rights Reserved</p>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

footer {
    background-color: $dl-dark;

    .container {
        max-width: 60%;
        margin-top: 2.5rem;
    }

    .hidden {
        visibility: hidden;
    }

    .row {
        padding-top: 2.5rem;
    }

    ul {

        list-style: none;
        padding: 0;
        line-height: 1.5rem;

        li {
            font-size: 0.7rem;

            a {
                color: $dl-light;
                text-decoration: none;
            }
        }
    }

    .copyright {

        width: 100%;
        padding-top: 3.5rem;
        padding-bottom: 1.5rem;

        p {
            color: $dl-light;
            font-size: 0.7rem;
        }
    }
}
</style>