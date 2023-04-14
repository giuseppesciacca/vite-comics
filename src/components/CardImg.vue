<script>
export default {
    props: {
        "thumb": string,
        "series": string
    },
}
</script>

<template>
    <img class="img-fluid" :src="thumb" alt="">

    <p class="py-3">{{ series }}</p>
</template>

<style lang="scss" scoped></style>