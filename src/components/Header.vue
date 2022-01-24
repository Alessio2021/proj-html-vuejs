.<template>
<header>
    <!-- slider -->
    <div id="CarouselArea" class="carousel slide position-relative" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="../assets/img/hero-07-2x.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="../assets/img/hero-08.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="../assets/img/hero-06-2x.jpg" class="d-block w-100" alt="...">
            </div>
        </div>
        <button class="my-btn-header position-absolute" type="button" data-bs-target="#CarouselArea" data-bs-slide="prev">
            <i class="fas fa-arrow-left my-arrow"></i>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="my-btn-header position-absolute my_next" type="button" data-bs-target="#CarouselArea" data-bs-slide="next">
            <i class="fas fa-arrow-right my-arrow"></i>
            <span class="visually-hidden">Next</span>
        </button>
        <!-- nav -->
        <nav>
            <div class="row position-absolute top-0 w-100 container-fluid ">
                <div class="col-4">
                    <a href="#">
                        <img class="my_img_header ms-5" src="../assets/img/author-logo-round-small.png" alt="">
                    </a>
                </div>
                <div class="col-8 d-flex justify-content-end">
                    <ul class="list-inline">
                        <li class="list-inline-item">
                            <a href="#">Home</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#">About Me</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#">Testimonials</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#">My Blog</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#">Meetups</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#">Shop</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#">Contact Me</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#"><i class="fas fa-shopping-cart"></i></a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- review -->
        <section class="review position-absolute">
            <div>
                <img src="" alt="">
            </div>
            <h2>Best-selling author and the most influential public intellectual in the western world right now.</h2>
            <h5>- The New York Time</h5>
        </section>
    </div>
</header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";

    .my-btn-header {
        width: 50px;
        height: 50px;
        bottom: 180px;
        left: 250px;
        border: 0;
        background-color: rgba(0,0,0,0.8);
        border-radius: 5px;
        .my-arrow {
            font-size: 1em;
            color: white;
        }
    }
    .my_next{
        left: 300px;
        margin-left: 5px;
    }
    .my_img_header {
        top: 0;
        left: 200px;
    }
    nav {

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
    }
</style>