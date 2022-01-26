.<template>
  <footer class="overflow-hidden">
    <div class="row">
      <div class="container">
        <div class="col position-relative">
          <div class="bg-footer"></div>
          <img class="position-absolute logo" src="../assets/img/author-logo-round-small.png" alt="">
            <div class="footer-text row position-absolute">
              <div class="col-4">
                <h2 class="text-uppercase fontNewYorkTimes text-light">about me</h2>
                <p class="grey">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dignissimos laboriosam ipsum voluptates repellat id libero distinctio quas? Quod fugit fugiat adipisci quia tempore.</p>
              </div>
                <FooterLinks />
              <!-- <div class="col-4">
                <h2 class="text-uppercase fontNewYorkTimes text-light">useful links</h2>
                <ul class="link list-group grey list-inline">
                  <li class="">
                    <a class="grey text-decoration-none" href=""><i class="fas fa-chevron-right pe-3"></i>Latest Books</a>
                  </li>
                  <li class="">
                    <a class="grey text-decoration-none" href=""><i class="fas fa-chevron-right pe-3"></i>Upcoming Events</a>
                  </li>
                  <li class="">
                    <a class="grey text-decoration-none" href=""><i class="fas fa-chevron-right pe-3"></i>Recent Articles</a>
                  </li>
                  <li class="">
                    <a class="grey text-decoration-none" href=""><i class="fas fa-chevron-right pe-3"></i>Business Enquiries</a>
                  </li>
                  <li class="">
                    <a class="grey text-decoration-none" href=""><i class="fas fa-chevron-right pe-3"></i>Visit My Foundation</a>
                  </li>
                </ul>
              </div> -->
              <div class="col-4">
                <h2 class="text-uppercase fontNewYorkTimes text-light">Contact info</h2>
                <ul class="list-group grey list-inline">
                  <li class="">
                    <span>63 E. Studebaker Street Bolingbrook, IL 60440</span>
                  </li>
                  <li>
                    <span>Phone (800) 000-0000</span>
                  </li>
                  <li>
                    <span>Mobile (800) 000-0000</span>
                  </li>
                  <li>
                    <span>Email: info@your-company.com</span>                    
                  </li>
                </ul>
                <ul class="list-inline">
                  <li class="list-inline-item"><a class="text-secondary fs-4 pe-4" href="http://it-it.facebook.it
"><i class="fab fa-facebook-f"></i></a></li>
                  <li class="list-inline-item"><a class="text-secondary fs-4 pe-4" href="https://twitter.com"><i class="fab fa-twitter"></i></a></li>
                  <li class="list-inline-item"><a class="text-secondary fs-4 pe-4" href="https://www.instagram.com"><i class="fab fa-instagram"></i></a></li>
                  <li class="list-inline-item"><a class="text-secondary fs-4 pe-4" href="https://it.linkedin.com"><i class="fab fa-linkedin"></i></a></li>
                  <li class="list-inline-item"><a class="text-secondary fs-4 pe-4" href="https://www.youtube.com"><i class="fab fa-youtube"></i></a></li>
                </ul>
              </div>
          </div>          
          <div class="copyright text-center position-absolute">
            <p class="">&copy;Copyright 2012 - 2020 | Avada Theme by <strong class="text-light">ThemeFusion</strong> | All Rights Reserved | Powered by <strong class="text-light">WordPress</strong></p>
          </div>
          <div class="cookies position-absolute">
            <a href="#CarouselArea"><i class="fas fa-chevron-up text-light"></i></a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import FooterLinks from './FooterLinks.vue'
export default {
  name: 'Footer',
  components: {
    FooterLinks,
  },
  data() {
    return {
      
    }
  },
}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";
  .grey {
      color: $suvaGray;
  }
  .fontNewYorkTimes {
      font-family: $fontNewYorkTimes;
  }

  .bg-footer {
    background-image: url(../assets/img/hero-07-2x.jpg);
    height: 500px;
    background-size: cover;
    filter: brightness(40%);
  }
  .logo {
    top: 100px;
    left: 100px;
  }
  .footer-text {
    padding: 7em 25em;
    top: 0;
    a:hover,
    a:hover i{
      color: $saffron;
    }

  }
  .copyright {
    bottom: 40px;
    left: 30%;
    color: grey;
  }
  .cookies {
    background-color: #434343;
    bottom: 0;
    left: 90%;
    padding: 1px 15px;
    cursor: pointer;
    border-radius: 5px 5px 0 0;
  }

</style>