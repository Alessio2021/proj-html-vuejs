.<template>
<header>
    <!-- fixed-right horizontal -->
    <section class="horizontal-fixed text-center">
        <div class="square-fixed">
            <i class="text-center fas fa-folder-open"></i>
            <h6>Demos</h6>
        </div>
        <div class="square-fixed">
            <span class="text-success">$</span>
            <span class="fs-2 text-success">39</span>
            <h6>On Sale</h6>
        </div>
    </section>
    <!-- slider -->
    <div id="CarouselArea" class="carousel slide position-relative w-100" data-bs-ride="carousel">
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
        <Navbar/>
        <!-- review -->
        <section class="review position-absolute">
            <h2 class="signature">Damon Vaughn</h2>
            <h2 class="fontNewYorkTimes">Best-selling author and the most influential public intellectual in the western world right now.</h2>
            <h5 class="suvaGray">- The New York Time</h5>
        </section>
        <!-- new release -->
        <section class="newRelease position-absolute">
            <div class="row">
                <div class="col-5">
                    <img src="../assets/img/book-widget.png" alt="">
                </div>
                <div class="col-7 w-50 pt-3">
                    <h3>Latest Book Release</h3>
                    <h5>D.VAUGHN AUTOBIOGRAPHY</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas tempora qui ea magni quae illo. </p>
                </div>
            </div>
            <div class="row d-flex justify-content-end">
                <div class="col text-center">
                    <a href="http://www.amazon.it/" class="sx"><i class="fab fa-amazon"></i> Buy On Amazon</a>
                    <a href="https://www.apple.com/it/app-store/" class="dx"><i class="fab fa-apple"></i> Buy On AppStore</a>
                </div>
            </div>
        </section>
    </div>
</header>
</template>

<script>
import Navbar from './Navbar.vue'
export default {
    name: 'Header',
    component: {
        Navbar,
    },
    data() {
        return {
            
        }
    },
}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";
    .carousel-inner {
        img {
            filter: brightness(0.40)
        }
    }
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
    .review {
        bottom: 300px;
        left: 250px;
        width: 850px;
        .signature {
            font-family: $fontSignature;
            color: $saffron;
            font-size: 4em;
            
        }
        .fontNewYorkTimes {
            font-family: $fontNewYorkTimes;
        }
        .suvaGray {
            color: $suvaGray;
            font-style: italic;
        }
        h2 {
            font-size: 3em;
            color: $white;

        }
    }
    .newRelease{
        width: 35%;
        height: 40%;
        padding: 2em;
        background-color: $white;
        bottom: 0;
        left: 65%;
        a {
            padding: 0.5em 2.5em;
            background-color: #F5FCFA;
            border: 2px solid #A4D2C2;
            text-decoration: none;
            color: black;
            box-shadow: 5px 10px 18px #A4D2C2;
            
        }
        a.sx{
            border-radius: 10px 0 0 10px;
        }
        a.dx{
            border-radius: 0 10px 10px 0;
        }
    }
    .horizontal-fixed {
        position: fixed;
        top: 100px;
        left: 95%;
        z-index: 1030;
        .square-fixed {
            width: 70px;
            height: 70px;
            background-color: #ffffff;
            border-radius: 5px;
            padding: 5px;
            margin: 1em;
            box-shadow: 0px 5px 10px #2c2e2d;
            i {
                color: #33475B;
                font-size: 2em;
            }
            span {
                line-height: 35px;
            }
        }
    }
        
</style>