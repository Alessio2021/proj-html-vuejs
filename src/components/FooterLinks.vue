.<template>
    <div class="col-4">
        <h2 class="text-uppercase fontNewYorkTimes text-light">useful links</h2>
        <ul class="link list-group grey list-inline">
            <li
                v-for="(link, index) in linksFooter"
                :key="index"
            >
            <a class="grey text-decoration-none" href=""><i class="fas fa-chevron-right pe-3"></i>{{link.text}}</a>
            </li>
            <!-- <li class="">
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
            </li> -->
        </ul>
    </div>
</template>

<script>
export default {
    name: 'FooterLinks',

    data() {
        return {
            linksFooter: [
                {
                    text: 'Latest Books'
                },
                {
                    text: 'Upcoming Events'
                },
                {
                    text: 'Recent Articles'
                },
                {
                    text: 'Business Enquiries'
                },
                {
                    text: 'Visit My Foundation'
                },
            ]
        }
    },
}
</script>

<style>

</style>