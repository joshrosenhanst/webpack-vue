<template>
  <div id="app">
    <main id="site-main">
      <h1>Hello World</h1>
      <img src="assets/img/vue_logo.png" alt="Vue logo">
    </main>
    <dog-footer />
  </div>
</template>

<script>
import DogFooter from './DogFooter.vue';
export default {
  name: 'App',
  components: {
    DogFooter
  }
}
</script>

<style lang="sass" scoped>
  #site-main>img
    width: 100px
</style>


