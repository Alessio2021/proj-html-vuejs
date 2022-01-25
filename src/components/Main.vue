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
        <section class="jumbotronAudible">
            <div class="container">
                <div class="row">
                    <div class="col-6">

                    </div>
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
        
    }
</style>