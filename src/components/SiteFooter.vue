<script>
export default {
    name: 'SiteFooter',
    data() {
        return {
            linkAddress: [
                {
                    name: '382 NE 191st St # 87394 Miami, FL 33179-3899',
                    href: '#'
                },
                {
                    name: '+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)',
                    href: '#'
                },
                {
                    name: 'support@maxcoach.com',
                    href: '#'
                },
            ],
            linkExplore: [
                {
                    name: 'Start here',
                    href: '#'
                },
                {
                    name: 'Blog',
                    href: '#'
                },
                {
                    name: 'About us',
                    href: '#'
                },
            ],
            linkPlaceholder: [
                {
                    name: 'Success story',
                    href: '#'
                },
                {
                    name: 'Courses',
                    href: '#'
                },
                {
                    name: 'Contact us',
                    href: '#'
                },
            ],
            linkInformation: [
                {
                    name: 'Membership',
                    href: '#'
                },
                {
                    name: 'Purchase guide',
                    href: '#'
                },
                {
                    name: 'Privacy policy',
                    href: '#'
                },
                {
                    name: 'Terms of service',
                    href: '#'
                },
            ],
        }
    },
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
                        <li v-for="link in linkAddress"><a href="{{link.href}}">{{ link.name }}</a></li>
                    </ul>
                    <div class="social_media"></div>
                </div>
                <div class="col d-flex">
                    <div class="col">
                        <h6 class="text-white fw-bold">Explore</h6>
                        <ul>
                            <li v-for="link in linkExplore"><a href="{{link.href}}">{{ link.name }}</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h6 class="hidden">Placeholder</h6>
                        <ul>
                            <li v-for="link in linkPlaceholder"><a href="{{link.href}}">{{ link.name }}</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h6 class="text-white fw-bold">Information</h6>
                        <ul>
                            <li v-for="link in linkInformation"><a href="{{link.href}}">{{ link.name }}</a></li>
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