.<template>
<div>
    <div 
        v-for="(event, index) in events"
        :key="index"
        class="col-4 text-center my_card p-3"
        >
        <div>
            <img class="w-100" :src="`../assets/img/${event.img}`" alt="">
        </div>
        <div class="bg-light p-2">
            <h4 class="p-3 eventTitle">{{event.eventName}}</h4>
            <div class="hr"></div>
            <p class="p-3">{{event.description}}</p>
        </div>
    </div>
</div>
</template>

<script>

export default {
    name: 'Event',

    data() {
        return {
            events: [
                {
                    eventName: 'Chicago Book Signing',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum et, quo corrupti qui, ipsum cupiditate ipsa nihil neque nesciunt.',
                    img: 'event-05-400x240.jpg'
                },
                {
                    eventName: 'Met &amp; Greet With Amanda',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum et, quo corrupti qui, ipsum cupiditate ipsa nihil neque nesciunt.',
                    img: 'event-04-400x240.jpg'

                },
                {
                    eventName: 'Open Book: Dialogues',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum et, quo corrupti qui, ipsum cupiditate ipsa nihil neque nesciunt.',
                    img: 'event-07-400x240.jpg'

                }
            ]
        }
    },
}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";
    .hr {
        width: 70%;
        height: 2px;
        background-color: rgba(0, 0, 0, 0.452);
        margin: auto;
    }
</style>