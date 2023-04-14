<script>
import BannerMain from './BannerMain.vue';
export default {
    name: "AppMain",
    components: {
        BannerMain
    }
}
</script>

<template>
    <main id="app_main" class=" debug">

        <div class="container px-3 py-5">
            <div>Content goes here</div>
        </div>

        <BannerMain></BannerMain>
        <!-- /.nav_main -->

    </main>
</template>

<style lang="scss" scoped>
main.debug {
    background-color: rgba(28, 28, 28, 1);
    color: white;
}
</style>