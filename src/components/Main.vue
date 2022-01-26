.<template>
    <main>
        <!-- meet The Author -->
        <section id="about-me" class="meetTheAuthor container my-5">
            <div class="row">
                <div class="col text-center">
                    <h4 class="signature">More About Damon Vaughn</h4>
                    <p class="fs-3 mt-3">Damon Vaughn is a professor of psicology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller "The story of my life."</p>
                    <button type="button" class="btn btn-success mt-3 px-4 py-2">Meet The Author</button>
                </div>
            </div>
        </section>
        <!-- stores -->
        <section id="shop" class="store">
            <div class="container">
                <div class="row py-5">
                    <div class="col-3">
                        <a href="http://www.ebay.it">
                            <img src="../assets/img/ebay-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="http://www.audible.it/">
                            <img src="../assets/img/audible-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="http://www.barnesandnoble.com">
                            <img src="../assets/img/bb-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="http://www.amazon.it/">
                            <img src="../assets/img/kindlefire-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                </div>
            </div>
            
        </section>
        <!-- jumbostron Audiobook -->
        <section class="jumbotronAudible">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <div class="phonePicture"></div>
                    </div>
                    <div class="text-jumbo col-6">
                        <div class="text-center">
                            <h2 class="fontNewYorkTimes text-light">New Audiobook</h2>
                            <h5 class="saffron pt-2">NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h5>
                            <p class="suvaGray pt-2">Expedita consectetur exercitationem nesciunt rem mollitia officiis explicabo ea, quas numquam nostrum </p>
                            <div class="row pt-2">
                                <div class="col-4">
                                    <img src="../assets/img/audible-logo.png" alt="">
                                </div>
                                <div class="col-4">
                                    <img src="../assets/img/bn-logo-tall.png" alt="">
                                </div>
                                <div class="col-4">
                                    <img src="../assets/img/kindle-logo-tall.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </section>
        <!-- Testimonials -->
        <section id="testimoni" class="testimonials container py-5">
            <div class="row">
                <div class="col-6">
                    <h2 class="fontNewYorkTimes">What The Crities Say</h2>
                    <p class="text-uppercase text-lagoon">Testimonials from around the world</p>
                </div>
                <div class="col-6 d-flex justify-content-end align-items-center">
                    <button type="button" class="btn btn-warning text-light">Read All Testimonials</button>
                </div>
            </div>
            <div class="row">
                <div class="col-7 position-relative">
                    <div class="reviewShowed"></div>
                    <div class="review_my text-light p-3 position-absolute">
                        <div class="p-5 text-testimonial">
                            <h2 class="fontNewYorkTimes">Best Author Of His Generation</h2>
                            <hr>
                            <h5>This book will change your prospective of life</h5>
                            <p class="pt-4">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. At molestias voluptatibus dolore, laboriosam assumenda culpa. Error odit explicabo illo, dicta fugiat voluptatem nihil, voluptate sapiente dolor minus deleniti ullam ea.
                            </p>
                            <p class="pt-4">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. At molestias voluptatibus dolore, laboriosam assumenda culpa. Error odit explicabo illo, dicta fugiat voluptatem nihil, voluptate sapiente dolor minus deleniti ullam ea.
                            </p>
                            <p class="pt-4">
                                <strong>
                                    <a href="https://www.nytimes.com">
                                        <img src="../assets/img/nytimes-logo-white-xsmall.png" alt="new york times site">
                                    </a>
                                    Justin Kilpatrick, <span class="text-lagoon">The New York Times</span>
                                </strong>
                            </p>
                        </div>
                    </div>
                </div>
                <Testimonials />
            </div>
        </section>
        <!-- events -->
        <section id="meet" class="events py-5 store">
            <div class="container">
                <div class="row">
                    <div class="col text-center">
                        <h2 class="fontNewYorkTimes">Upcoming Events</h2>
                        <p class="uppercase saffron">meet the author in person</p>
                    </div>
                </div>
                <Event />
            </div>
        </section>
        <!-- jumbo Subscriber -->
        <section class="jumbotronSub">
            <div class="container">
                <div class="row d-flex justify-content-center">
                    <div class="col-5 text-center subscriberPadding">
                        <h2 class="fs-1 fontNewYorkTimes text-light">Subscribe To My Newsletter</h2>
                        <p class="saffron text-uppercase">be notified about book signing tour dates</p>
                        <form action="">
                            <input v-model="registerEmail" class="me-1" type="text" placeholder="Insert your email ... *">
                            <button type="button" class="btn btn-success ms-1 px-4">Subscribe</button>
                        </form>
                        <p class="grey">Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat dolore possimus optio fugit ipsa quia libero voluptas earum.</p>
                    </div>
                </div>

            </div>
        </section>
        <!-- more info -->
        <section class="info container py-5">
            <div class="row">
                <div class="col text-center py-5">
                    <h2 class="fontNewYorkTimes">Dig A Little Deeper Into Damo Vaughn</h2>
                    <p class="text-uppercase text-lagoon">find out more about the author himself</p>
                </div>
                <MoreInfo/>
            </div>
        </section>
        <!-- last articles -->
        <section class="lastArticles store py-5">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <h2 class="fontNewYorkTimes">Recent Atricles</h2>
                        <p class="text-uppercase text-lagoon">read the latest entries</p>
                    </div>
                    <div class="col-6 d-flex justify-content-end align-items-center">
                        <button type="button" class="btn btn-warning text-light px-5">All Articles</button>
                    </div>
                </div>
                <div class="row">
                    <div class="col-8 bg-light">
                        <div class="p-4">
                            <div class="img-lastArticles"></div>
                        </div>
                        <div class="p-5 ">
                            <h5>20 Creativity Tips</h5>
                            <p class="smallSize pb-2 grey">By <strong>admin</strong> | October 24th, 2019 | Categories: <strong>Event, Tips &amp; Tricks</strong></p>
                            <p class="fs-5 grey">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus porro adipisci iure. Temporibus aliquid quis sequi voluptatem quod fugiat id natus.</p>
                        </div>
                    </div>
                    <div class="col-4 bg-light">
                        <div class="">
                            <div class="p-4">
                                <div class="img-booklist"></div>
                            </div>
                            <div class="px-4">
                                <h5>What's On Your Booklist?</h5>
                                <p class="smallSize pb-2 grey">By <strong>admin</strong> | October 24th, 2019 | <strong>0 Comments</strong></p>
                            </div>
                        </div>
                        <div class="">
                            <div class="p-4">
                                <div class="img-travel"></div>
                            </div>
                            <div class="px-4">
                                <h5>Instabul Travel Guide</h5>
                                <p class="smallSize pb-2 grey">By <strong>admin</strong> | October 24th, 2019 | <strong>0 Comments</strong></p>
                            </div>
                        </div>                        
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<script>
import Event from './Event.vue'
import MoreInfo from './MoreInfo.vue'
import Testimonials from './Testimonials.vue'

export default {
    name: 'Main',
    components: {
        Event,
        MoreInfo,
        Testimonials,
    },
    data() {
        return {
            registerEmail: '',
        }
    },
}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";
    .saffron {
        color: $saffron;
    }
    .grey {
        color: $suvaGray;
    }
    .text-lagoon {
        color: $blueLagoon;
    }
    .fontNewYorkTimes {
        font-family: $fontNewYorkTimes;
    }
    .meetTheAuthor {
        padding: 4em;
        .signature {
            font-family: $fontSignature;
            color: $saffron;
            font-size: 4em;
        }
    }
    .jumbotronAudible {
        background-image: url(../assets/img/banner.jpg);
        height: 670px;
        background-repeat: no-repeat;
        background-size: cover;
        .phonePicture {
            background-image: url(../assets/img/audible-app-2x-600x628.png);
            margin-top: 5em;
            height: 590px;
            background-repeat: no-repeat;
            background-size: contain;
        }
        
        .suvaGray {
            color: $suvaGray;
        }
        
        .text-jumbo {
            display: flex;
            align-items: center;
            padding: 4em;
        }
    }
    .testimonials {
        margin-top: 5em;
        button {
            margin: 2em;
            padding: 0.5em 2.5em;
            background-color: $saffron;
        }
        .reviewShowed {
            background-image: url(../assets/img/testimonial2-2x.jpg);
            background-size: cover;
            height: 650px;
            border-radius: 0 0 100px 0;
            filter: brightness(65%);
            transition: 1s;
            &:hover {
                transform: scale(1.1);
            }
        }
        .review_my {
            width: 90%;
            top: 100px;
            left: 15px;
        }
    }
    .events {
        .my_card {
            border: none;
            transition: 1s;
            cursor: pointer;
            &:hover {
                opacity: 0.7;
            }
        }


    }
    .jumbotronSub {
        background-image: url(../assets/img/banner-2.jpg);
        background-size: cover;
        .subscriberPadding {
            padding: 7em 0;
        }
    }
    .info {
        .img-aboutme {
            background-image: url(../assets/img/box-1.jpg);
            height: 100%;
            border-radius: 0 0 100px 0;
            filter: brightness(65%);
        }
        .img-lastbook {
            background-image: url(../assets/img/box-4.jpg);
            height: 100%;
            border-radius: 0 0 100px 0;
            filter: brightness(65%);
        }
        .img-signing {
            background-image: url(../assets/img/box-3.jpg);
            height: 100%;
            border-radius: 0 0 100px 0;
            filter: brightness(65%);
        }
        .my-card-info {
            width: 400px;
            height: 480px;
            transition: 1s;
            cursor: pointer;
            .text-info {
                transition: 1s;
            }
            &:hover {
                transform: scale(1.1);
            }
            &:hover .text-info{
                transform: scale(0.9);
            }
        }
    }
    .lastArticles {
        
        .img-lastArticles {
            background-image: url(../assets/img/20-Tips-800x471.jpg);
            height: 471px;
            width: 800px;

        }
        .smallSize {
            font-size: 0.8em;
        }
        .img-booklist {
            background-image: url(../assets/img/thumb-13-2x-320x202.jpg);
            height: 202px;
            width: 320px;
        }
        .img-travel {
            background-image: url(../assets/img/thumb-08-2x-320x202.jpg);
            height: 202px;
            width: 320px;
        }
    }
</style>