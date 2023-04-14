<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
}
</script>

<template>
  <AppHeader></AppHeader>
  <!-- /#app_header -->

  <AppMain></AppMain>
  <!-- /#app_main -->

  <AppFooter></AppFooter>
  <!-- /#app_footer -->
</template>

<style lang="scss" scoped></style>