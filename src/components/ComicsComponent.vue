<template>
    <div>
        <img :src="thumb">
        <small>{{price}}</small>
        <span>{{series}}</span>
        <span>{{type}}</span>
    </div>
</template>

<script>
export default {
    props:{
        img: String,
        price: Number,
        series: String,
        type: String
    }
}
</script>
