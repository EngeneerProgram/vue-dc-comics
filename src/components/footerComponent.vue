<template>
<div class="footer_container">
    <div class="container">
        <div class="i left">
            <button class="btn"><a href="#">Sign Up!</a></button>
        </div>

        <div class="i right">
            <span>Follow Us!</span>

            <img src="@/assets/img/footer-facebook.png" alt="">
            <img src="@/assets/img/footer-periscope.png" alt="">
            <img src="@/assets/img/footer-pinterest.png" alt="">
            <img src="@/assets/img/footer-twitter.png" alt="">
            <img src="@/assets/img/footer-youtube.png" alt="">

        </div>

        
    </div>
</div>

   
</template>


<style lang="scss" scoped>

.footer_container{
    width: 1905px;
    background-color:rgba(48, 48, 48, 1);
    height: 13vh;
    
    
}

.footer{
    
    background-color:rgba(48, 48, 48, 1);
    
   
}
.container{
    padding:30px;
    background-color: rgba(48, 48, 48, 1);
    display:Flex;
    justify-content: space-between;

    .i{
        color:white;
    }

    .btn{
        padding:15px 35px;
        border:5px solid rgba(2, 130, 249, 1);
        background-color: rgba(48, 48, 48, 1);

        a{
            color:white;
            text-decoration: none;
            text-transform: uppercase;
        }
       
    }

     span{
            text-transform: uppercase;
            color:rgba(2, 130, 249, 1);
            
        }

        .right{
            display: flex;
            align-content: center;
            align-items: center;
        }

        img{
            margin:10px;
        }
}
</style>