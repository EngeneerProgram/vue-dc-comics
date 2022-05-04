<template>
    <header>
        <div class="container">
            <div class="row align_center">
                <div class="coll_1">
                    <img class="logo" src="@/assets/img/dc-logo.png" alt="">
                </div>

                <div class="coll_7 m-left-auto">
                    <Navmenu />
                </div>
            </div>
        </div>
    </header>
</template>



<script>

import Navmenu from './NavbarComponent.vue';

export default {
    name: "HeaderComponents",
    components:{
        Navmenu
    }
}
</script>


<style lang="scss" scoped>
.logo{
    width: 100px;
}

header{
    padding-top:1rem;
    
}
</style>
