<template>
    <div class="jumbo">
        <div class="description">
            <h1>--> content goes here --></h1>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}
.jumbo{
    display:Flex;
    align-items: center;
    
    margin-top:2rem;
    width: 100%;
    height: 80px;
    background-color:black;
    &description{
        width: 1400px;
        
    }
    h1{
        color:white;
        margin-left:247px;
        
    }
}
</style>