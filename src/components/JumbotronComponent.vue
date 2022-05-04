<template>

   <div class="hero_jumbo">
       <span class="c_series">
           CURRENT SERIES
       </span>
   </div>
       
   
</template>

<script>

export default {
    
}
</script>

<style lang="scss" scoped>

.hero_jumbo {
    position:relative;
    background-image: url("../assets/img/jumbotron.jpg");
    height: 550px;
    
    
    .c_series{
        position:absolute;
        bottom:-30px;;
        left:300px;
        padding:14px 35px;
        border:5px solid rgba(2, 130, 249, 1);
        background-color:rgba(2, 130, 249, 1);
        text-transform: uppercase;
        font-weight: bold;
        color:white;

    }
}



</style>