<template>
    <div class="container_component">
        <div class="container">
            <div class="row">
                <div class="coll" v-for='({name}, index) in ListElement' :key='index'>
                    <div class="card">
                        <div class="img">
                            <img src="@/assets/img/buy-comics-merchandise.png" :alt="name">
                        </div>
                        <div class="text">
                            {{name}}
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "MainComponent",
    data(){
        return {
            ListElement:[
            {
                name: 'Digital Comics',
                img: 'src/assets/img/buy-comics-digital-comics.png'
            },

            {
                name: 'Dc Merchandise',
                img: 'src/assets/img/buy-comics-merchandise.png'
            },

            {
                name: 'Subscription',
                img: 'src/assets/img/buy-comics-subscriptions.png'
            },

            {
                name: 'Comics shop Locator',
                img: 'src/assets/img/buy-comics-shop-locator.png'
            },

            {
                name: 'Dc Power Visa',
                img: 'src/assets/img/buy-dc-power-visa.png'
            },


        ]
        }
    }
}
</script>

<style lang="scss" scoped>
.container_component{
    padding:3rem;
    background-color: rgba(2, 130, 249, 1);

    .card{
        display:flex;
        justify-content: center;
        align-content: center;
        align-items: center;
        column-gap: 1rem;
        img{
            width: 50px;
        }

        .text{
            color:white;
            text-transform: uppercase;
        }
    }
}
</style>