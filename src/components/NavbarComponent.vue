<template>
    <ul>
        <li  v-for="(nav, index) in NavMenu" :key="index">
            <a href="#">{{nav}}</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: "NavComponent",
    data(){
        return {
            NavMenu: [
                'CHARACTERS',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTABLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP'
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
ul{
    list-style: none;
    display:flex;
    padding:1rem;
    align-items:center;
    height: 100%;
    
    li{
        padding:10px;
    }

    a{
        text-decoration: none;
        text-transform: uppercase;
        color:black;
    }
}
</style>