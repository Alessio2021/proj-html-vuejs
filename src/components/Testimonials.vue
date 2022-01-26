.<template>
    <div class="col-5">
        <div class="ps-5 pb-4"
            v-for="(review, index) in reviews"
            :key="index"
        >
            <div class="store p-5 text-center">
                <h3 class="fontNewYorkTimes">{{review.title}}</h3>
                <p>{{review.description}}</p>
            </div>
            <h5 class="pt-2 align-middle d-inline">
                <img class="pe-4" :src="require(`../assets/img/${review.img}`)" alt="">
                <span class="grey"><strong>{{review.author}},</strong></span> {{review.journal}}
            </h5>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Testimonials',
    data() {
        return {
            reviews: [
                {
                    title: 'A True Masterpiece, Bravo!',
                    description: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Consectetur optio ipsam soluta mollitia quidem repellat laboriosam illo voluptates et, nam minima aut, modi laudantium obcaecati aliquam totam tenetur aperiam saepe?',
                    img: 'theguardian-xsmall.png',
                    author: 'Gerald Hendley',
                    journal: 'The Guardian',
                },
                {
                    title: 'A Unique View On The World',
                    description: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Consectetur optio ipsam soluta mollitia quidem repellat laboriosam illo voluptates et, nam minima aut, modi laudantium obcaecati aliquam totam tenetur aperiam saepe?',
                    img: 'globe-xsmall.png',
                    author: 'Mary Maxey',
                    journal: 'The Globe and Mail',
                }
            ]
        }
    },
}
</script>

<style>

</style>