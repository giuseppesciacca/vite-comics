<script>
export default {
    props: {
        thumb: String,
        series: String
    },
}
</script>

<template>
    <img class="img-fluid" :src="thumb" alt="">

    <p class="py-3">{{ series }}</p>
</template>

<style lang="scss" scoped>
img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    object-position: top;
}
</style>