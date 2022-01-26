.<template>
    <div class="row">
        <div class="col-4"
            v-for="(info, index) in infos"
            :key="index"
        >
            <div class="position-relative my-card-info">
                <div :class="`${info.img}`"></div>
                <div class="text-info position-absolute w-100">
                    <div class="text-center">
                        <h3 class="text-light py-2">{{info.coverTitle}}</h3>
                        <div class="infoHr"></div>
                        <p class="saffron py-2">{{info.description}}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MoreInfo',
    data() {
        return {
            infos: [
                {
                    coverTitle: 'About Me',
                    description: 'Lorem ipsum dolor sit amet',
                    img: 'img-aboutme'
                },
                {
                    coverTitle: 'My Latest Book',
                    description: 'Lorem ipsum dolor sit amet',
                    img: 'img-lastbook'
                   
                },
                {
                    coverTitle: 'Book Signing',
                    description: 'Lorem ipsum dolor sit amet',
                    img: 'img-signing'

                }
            ]
        }
    },
}
</script>

<style>

</style>