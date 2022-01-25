.<template>
    <main>
        <!-- meet The Author -->
        <section class="meetTheAuthor container my-5">
            <div class="row">
                <div class="col text-center">
                    <h4 class="signature">More About Damon Vaughn</h4>
                    <p class="fs-3 mt-3">Damon Vaughn is a professor of psicology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller "The story of my life."</p>
                    <button type="button" class="btn btn-success mt-3 px-4 py-2">Meet The Author</button>
                </div>
            </div>
        </section>
        <!-- stores -->
        <section class="store">
            <div class="container">
                <div class="row py-5">
                    <div class="col-3">
                        <a href="#">
                            <img src="../assets/img/ebay-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <img src="../assets/img/audible-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <img src="../assets/img/bb-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="#">
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
        <section class="testimonials container">
            <div class="row">
                <div class="col-6">
                    <h2 class="fontNewYorkTimes">What The Crities Say</h2>
                    <p class="text-uppercase">Testimonials from around the world</p>
                </div>
                <div class="col-6 d-flex justify-content-end">
                    <button type="button" class="btn btn-warning text-light">Read All Testimonials</button>
                </div>
            </div>
        </section>
    </main>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";
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
    .store {
        background-color: #FEF7E9;
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
        .saffron {
            color: $saffron;
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
    }
</style>