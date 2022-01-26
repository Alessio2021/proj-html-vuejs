<template>
    <nav>
        <div class="row position-absolute top-0 w-100 container-fluid ">
            <div class="col-4">
                <a href="#">
                    <img class="my_img_header ms-5" src="../assets/img/author-logo-round-small.png" alt="">
                </a>
            </div>
            <div class="col-8">
                <ul class="list-inline">
                    <li 
                        v-for="(link, index) in navLink"
                        :key="index"
                        class="list-inline-item">
                        <a :href="link.link">{{link.section}}</a>
                    </li>
                    <!-- <li class="list-inline-item">
                        <a href="#about-me">About Me</a>
                    </li>
                    <li class="list-inline-item">
                        <a href="#testimoni">Testimonials</a>
                    </li>
                    <li class="list-inline-item">
                        <a href="#">My Blog</a>
                    </li>
                    <li class="list-inline-item">
                        <a href="#meet">Meetups</a>
                    </li>
                    <li class="list-inline-item">
                        <a href="#shop">Shop</a>
                    </li>
                    <li class="list-inline-item">
                        <a href="#">Contact Me</a>
                    </li> -->
                    <li class="list-inline-item">
                        <a href="#"><i class="fas fa-shopping-cart"></i></a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>


</template>

<script>
export default {
    name: 'Navbar',
    data() {
        return {
            navLink: [
                {
                    section: 'Home',
                    link:'#',
                },
                {
                    section: 'About Me',
                    link:'#about-me',
                },
                {
                    section: 'Testimonials',
                    link:'#testimoni',
                },
                {
                    section: 'My Blog',
                    link:'#',
                },
                {
                    section: 'Meetups',
                    link:'#meet',
                },
                {
                    section: 'Shop',
                    link:'#shop',
                },
                {
                    section: 'Contact Me',
                    link:'#',
                },
            ]
            
        }
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";
    li {
        padding: 2em;
        border-top: 3px solid rgba(0, 0, 255, 0);
        a {
            text-decoration: none;
            color: white;
        }
    }
    li:hover {
        border-top: 3px solid $saffron;
    }
    li:hover a{
        color: $saffron;
    }
</style>