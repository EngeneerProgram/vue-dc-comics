<template>
    
        <header>
            <div class="container_menu">
                <div class="logo">
                    <WebLogo />
                </div>
                <nav>
                    <ul class="menu">
                        <li><a href="#">CHARACTERS</a></li>
                        <li><a href="#">COMICS</a></li>
                        <li><a href="#">MOVIES</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">GAMES</a></li>
                        <li><a href="#">COLLECTIBLES</a></li>
                        <li><a href="#">VIDEOS</a></li>
                        <li><a href="#">FANS</a></li>
                        <li><a href="#">NEWS</a></li>
                        <li><a href="#">SHOP</a></li>
                        
                    </ul>
                    
                </nav>
            </div>
            
        </header>
    
    
</template>


<script>
import WebLogo from '@/components/LogoComponent.vue'
export default {
    name: 'HeaderComponent',
    components : {
        WebLogo
    }
    
}
</script>


// stile
<style lang="scss" scoped>
.logo>img{
    width: 90px;
}
header{
    display:Flex;
    justify-content: center;
    background-color:white;

    .container_menu{
        display:Flex;
        width: 1400px;
        background-color:white;
        align-items: center;

        
    }

    nav{
        margin-left:auto;
        
         
        
    }

    .menu{
        display:flex;
    }

    ul{
        list-style: none;

        
    }
    li{
        padding:8px;
    }

    a{
        text-decoration: none;
        color:black;
    }
    
}

</style>