<template>
  <div id="app">
    <leo-header></leo-header>
  </div>
</template>

<script>
  import LeoHeader from './Header.vue'
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
    components: {
      LeoHeader
    }
}
</script>

<style>

</style>
